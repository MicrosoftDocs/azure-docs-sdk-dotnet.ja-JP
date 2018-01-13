<Type Name="BatchRequestModificationInterceptHandler" FullName="Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler">
  <TypeSignature Language="C#" Value="public delegate void BatchRequestModificationInterceptHandler(IBatchRequest request);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed BatchRequestModificationInterceptHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub BatchRequestModificationInterceptHandler(request As IBatchRequest)" />
  <TypeSignature Language="F#" Value="type BatchRequestModificationInterceptHandler = delegate of IBatchRequest -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="request" Type="Microsoft.Azure.Batch.Protocol.IBatchRequest" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="request">傍受される要求のパラメーターです。</param>
    <summary>
            パラメーターを変更するために、Batch service への要求をインターセプトするメソッドを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>