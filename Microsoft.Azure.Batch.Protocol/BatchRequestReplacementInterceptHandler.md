<Type Name="BatchRequestReplacementInterceptHandler" FullName="Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler">
  <TypeSignature Language="C#" Value="public delegate void BatchRequestReplacementInterceptHandler(ref IBatchRequest request);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed BatchRequestReplacementInterceptHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequestReplacementInterceptHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub BatchRequestReplacementInterceptHandler(ByRef request As IBatchRequest)" />
  <TypeSignature Language="F#" Value="type BatchRequestReplacementInterceptHandler = delegate of  -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="request" Type="Microsoft.Azure.Batch.Protocol.IBatchRequest&amp;" RefType="ref" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="request">傍受される要求のパラメーターです。</param>
    <summary>
            パラメーターや操作コンテキストを交換するために、Batch service への要求をインターセプトするメソッドを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>