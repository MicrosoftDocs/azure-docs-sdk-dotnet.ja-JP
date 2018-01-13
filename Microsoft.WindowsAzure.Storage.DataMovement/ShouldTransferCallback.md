<Type Name="ShouldTransferCallback" FullName="Microsoft.WindowsAzure.Storage.DataMovement.ShouldTransferCallback">
  <TypeSignature Language="C#" Value="public delegate bool ShouldTransferCallback(object source, object destination);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ShouldTransferCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.ShouldTransferCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function ShouldTransferCallback(source As Object, destination As Object) As Boolean " />
  <TypeSignature Language="F#" Value="type ShouldTransferCallback = delegate of obj * obj -&gt; bool" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="source" Type="System.Object" />
    <Parameter Name="destination" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Boolean</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="source">転送元のインスタンス。</param>
    <param name="destination">転送先のインスタンス。</param>
    <summary>
            転送を行う必要があるかどうかを通知呼び出されるコールバック。
            </summary>
    <returns>True の場合は、転送を行う必要があります。それ以外の場合は false。</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>