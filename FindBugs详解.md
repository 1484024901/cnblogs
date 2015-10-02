## Find bugs�󱨸澯����������
	
### ��������

��java�����У�Find bugs�ľ�̬����ܹ����������ھ��������ܴ��ڵ�ȱ�ݡ�����ʵ��ʹ�õĹ����У�Ҳȷʵ�������������ڡ�ȱ��else��֧�����¡�����δ��ʼ�����󡱵Ĵ�����֮���Ӧ���ǣ�ͨ��Find bugsҲ�����Ĵ�������ʹ�þ�̬��Ա����Find bugs�澯�������ͨ����ϸ�Ķ��ͷ��������߼�������ȷ�ϴ��뱾��û�����⣬���������Find bugs�󱨵��������Ȼ���Ǵ���ʹ��Find bugs��������ľ�̬��飬��ô���б�Ҫ����һ���ɾ��Ĵ��뻷����������û���κε�Find bugs�澯�����ȷ���Ǵ������⣬����������Ҫ���Ͼ��������ȷ����Find bugs�󱨣�ҲӦ�ý����������Ա�����ļ���ܹ�����һ���ɾ��Ļ�����ͬ�����󱨲���Ҫ����ȷ�ϡ�Find bugs�澯�󱨵������ǳ����ף�ֻ��Ҫ�����������༶��ͷ������У�����Find bugs��ע��Ϳ������������ｨ�������������ڷ��������Ͻ��У��Կ����������ķ�Χ������޶ȷ��ý������Ĵ�������Ҳ��Ϊ�󱨸����ص��ˡ�

### ����

* �ڹ������ע��������jar����ʹ��Find bugsע����Ҫ�õ�����jar����annotations.jar��jsr305.jar����eclipse��װ��Find bugs�������eclipseĿ¼�¿����ҵ�������jar���ļ���
* ���ע�⣺�����ʴ������ڵ�����߷���ǰ�����ע�⡣���У�value��ֵ����ǰ���ᵽ��find bugs�澯��Ϣ�е�ģʽ����Ϊvalue��һ�����飬���Կ���ͬʱ��Ӷ��ģʽ��justification��ֵ��һ��������Ϣ����������Ϊ������ע���ע�ͣ����ݿ���������ġ�

������java
	@edu.umd.cs.findbugs.annotations
	SuppressWarnings(value={"NM_CONFUSING"}, justification="remove findbugs")
������


* ��������Find bugs���м�飺�����ע��󣬽�����Ӧ����������find bugs���߽��м�飬��ȷ�����Ѿ���������

## MS: Field should be package protected (MS_PKGPROTECT)

A mutable static field could be changed by malicious code or by accident. The field could be made package protected to avoid this vulnerability.

�����������˶�����飬��ʹ���� public final static ���η���

������java
	public final static double[][][] Y_MIN_SCOPE=
	{
		{{-120, -25}},
		{{0, 254}},
		{{0, 254}},
		{{0, 254}}
	    
	};
    public final static double[] GRID_HEIGHT = {1,1,1,1};

 	public final static String[][] TAG_NAMES=
	{
		{"RSRQ(dB)","RSRP(dBm)"},
		{"TA(16*Ts)","UE TxPower(dBm)"},
		{"TA(16*Ts)","RSRP(dBm)"},
		{"TA(16*Ts)","RSRQ(dB)"}
	};
������

findbugs�����޸���ʾ�ǣ�

������
	In LTE3DConstant 
	Field LTE3DConstant.Y_MIN_SCOPE 
	At LTE3DConstant.java:[line 53] 
	Y_MIN_SCOPE should be package protected 
	Bug Type: MS_PKGPROTECT 
	Bug Category:MALICIOUS_CODE (Malicious code vulnerability) 
	Source File: 
	Line:53
������

�޸ĳ������Ͳ������ˡ�

������java
	protected final double[][][] Y_MIN_SCOPE=
	{
		{{-120, -25}},
		{{0, 254}},
		{{0, 254}},
		{{0, 254}}
	    
	};
������

����ԭ������Ϊ�����ط�û��ʹ�õ������ı�����������ý�public�ĳ�protected������ΪʲôҪȥ��static���ǲ���⡣
