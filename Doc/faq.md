## ִ��Patch for android����Patch for iosʱ������"please put template file for android/ios in IFixToolKit directory!��

������������Ҫ����һ������ģ���ļ��ŵ�IFixToolKitĿ¼��

* ��������������android��ģ�棬��ִ��һ����ͨ��android�������ڹ����Ĺ����У���������Ŀ¼/Temp��Ŀ¼��UnityTempFile��ͷ���ļ�����������������һ����UnityTempFile��ͷ�����ļ�������ոմ���������ļ������Ը����ļ�ʱ������ļ���ͷ�������в�����ios������ôһ�У�-define:UNITY_IOS��android����-define:UNITY_ANDROID�����ұ���û��UNITY_EDITOR���ҵ�����������IFixToolKitĿ¼���������window��ȡ��UnityTempFile��������Ϊandroid.win.tpl�������mac�»�ȡ�ģ�������Ϊandroid.osx.tpl�����ⲽ����һ����Ŀ������㲻����unity�汾����������������꣬������һ�μ��ɣ�
* ios��ģ���ļ�����Ϊios.osx.tpl�������ϣ����window������ios����������һ�ݸ���Ϊios.win.tpl��������ļ��������ӵ�����dll��ϵͳ��dll��·����window��unity��װĿ¼�޸ġ�

## IL2CPP ���ֱ���`IL2CPP error for method 'System.Object IFix.Core.EvaluationStackOperation::ToObject(IFix.Core.Value*,IFix.Core.Value*,System.Object[],System.Type,IFix.Core.VirtualMachine,System.Boolean)'`

Ӧ�����Լ��ֶ�����`IFix.Core.dll`����

�޸�iFix.CoreԴ�������Ҫͨ��`build_for_unity.bat`�ű����й���

## ���� Patch ��ʱ������`Error: the new assembly must not be inject, please reimport the project!`����

���� Patch �� dll�����ܽ���ע��

## ���������������������δ���

�����Unity2018.3�汾�����ϣ�����Unity������C#����ӿڣ�����InjectFix��Unity2018.3�汾ֱ��֧��Android��iOS�Ĳ������ɣ�ֱ��ִ�ж�Ӧ�˵����ɡ�

���������Unity2018.3�汾����Ҫ�ñȽ��鷳�ķ�ʽ������Ӧƽ̨�ı��������Assembly-CSharp.dll���������Ȼ�����IFix.Editor.IFixEditor.GenPatchȥ���ɲ�����

Unity�������ڹ��̵�TempĿ¼�½�һ���ļ����������в����ŵ��Ǹ��ļ���Ȼ��ִ�����ƣ�Ŀ¼�����Լ���unity��װ�������������������б��룺

~~~bash
"D:\Program Files\Unity201702\Editor\Data\MonoBleedingEdge\bin\mono.exe" "D:\Program Files\Unity201702\Editor\Data\MonoBleedingEdge\lib\mono\4.5\mcs.exe"  @Temp/UnityTempFile-55a959adddae39f4aaa18507dd165989
~~~

����Գ���һ�α༭���µ��ֻ��汾�����Ȼ�󵽹���Ŀ¼�µ�TempĿ¼���Ǹ���ʱ�ļ�������������������Զ�ɾ��������Ҫ�ֿ죩��

����ļ�������ط��������ģ������Ҫ��C#�ļ��б����Ը�Ϊ��̬��������ļ���C#�ļ��б���ݵ�ǰ��Ŀ���ɣ��������ֲ��䡣Ȼ��������ļ���Ϊ���������롣
