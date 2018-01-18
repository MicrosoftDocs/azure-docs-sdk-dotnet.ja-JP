<Type Name="RetryPolicy" FullName="Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy">
  <TypeSignature Language="C#" Value="public abstract class RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RetryPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="705ee-101">さまざまな種類の再試行ポリシーによって immplemented を抽象クラス</span><span class="sxs-lookup"><span data-stu-id="705ee-101">Abstract class immplemented by different types of retry policies</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RetryPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public abstract bool ShouldRetry (int httpCode, Exception ex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 httpCode, class System.Exception ex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy.ShouldRetry(System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ShouldRetry (httpCode As Integer, ex As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * Exception -&gt; bool" Usage="retryPolicy.ShouldRetry (httpCode, ex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpCode" Type="System.Int32" />
        <Parameter Name="ex" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="httpCode"></param>
        <param name="ex"><span data-ttu-id="705ee-102">Httprequest 中見た最後の例外</span><span class="sxs-lookup"><span data-stu-id="705ee-102">Last exception that we saw during Httprequest</span></span></param>
        <summary>
            <span data-ttu-id="705ee-103">HttpRequest を再試行するかどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="705ee-103">Determines whether the HttpRequest should be retried</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>