<Type Name="SetAttributesCallback" FullName="Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback">
  <TypeSignature Language="C#" Value="public delegate void SetAttributesCallback(object destination);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SetAttributesCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub SetAttributesCallback(destination As Object)" />
  <TypeSignature Language="F#" Value="type SetAttributesCallback = delegate of obj -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="destination" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="destination">上書きする移行先のインスタンス。</param>
    <summary>
            属性を設定する移行先のメモリ内で呼び出されるコールバック。 このコールバックで設定した属性は、azure ストレージ サービスに送信されます。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>