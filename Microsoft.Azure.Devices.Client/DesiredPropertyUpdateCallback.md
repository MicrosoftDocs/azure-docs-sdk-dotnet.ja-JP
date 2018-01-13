<Type Name="DesiredPropertyUpdateCallback" FullName="Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback">
  <TypeSignature Language="C#" Value="public delegate System.Threading.Tasks.Task DesiredPropertyUpdateCallback(TwinCollection desiredProperties, object userContext);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DesiredPropertyUpdateCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.DesiredPropertyUpdateCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function DesiredPropertyUpdateCallback(desiredProperties As TwinCollection, userContext As Object) As Task " />
  <TypeSignature Language="F#" Value="type DesiredPropertyUpdateCallback = delegate of TwinCollection * obj -&gt; Task" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="desiredProperties" Type="Microsoft.Azure.Devices.Shared.TwinCollection" />
    <Parameter Name="userContext" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Threading.Tasks.Task</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="desiredProperties">サービスから受信した更新プログラムに含まれていたプロパティ</param>
    <param name="userContext">コールバックの登録時に渡されるコンテキスト オブジェクト</param>
    <summary>
            目的のプロパティの更新プログラムのコールバック デリゲート。  これは、パッチ、サービスから受信するたびに呼び出されます。
            </summary>
    <returns>To be added.</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>