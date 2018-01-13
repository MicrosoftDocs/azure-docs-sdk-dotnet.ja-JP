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
    <param name="request"><span data-ttu-id="b556c-101">傍受される要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b556c-101">The parameters of the request being intercepted.</span></span></param>
    <summary>
            <span data-ttu-id="b556c-102">パラメーターや操作コンテキストを交換するために、Batch service への要求をインターセプトするメソッドを表します。</span><span class="sxs-lookup"><span data-stu-id="b556c-102">Represents a method that intercepts a request to the Batch service in order to replace the parameters and/or operation context.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>