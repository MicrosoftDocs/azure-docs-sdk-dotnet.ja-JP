<Type Name="IResourceResponse&lt;TResource&gt;" FullName="Microsoft.Azure.Documents.Client.IResourceResponse&lt;TResource&gt;">
  <TypeSignature Language="C#" Value="public interface IResourceResponse&lt;TResource&gt; : Microsoft.Azure.Documents.Client.IResourceResponseBase where TResource : Resourcenew()" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IResourceResponse`1&lt;.ctor (class Microsoft.Azure.Documents.Resource) TResource&gt; implements class Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IResourceResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IResourceResponse(Of TResource)&#xA;Implements IResourceResponseBase" />
  <TypeSignature Language="F#" Value="type IResourceResponse&lt;'Resource (requires 'Resource :&gt; Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; = interface&#xA;    interface IResourceResponseBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TResource">
      <Constraints>
        <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
        <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IResourceResponseBase</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TResource"><span data-ttu-id="c3f31-101">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="c3f31-101">The resource type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="c3f31-102">Azure Cosmos DB サービスの目的をモックに公開されるインターフェイス。</span><span class="sxs-lookup"><span data-stu-id="c3f31-102">Interface exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public TResource Resource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TResource Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.IResourceResponse`1.Resource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resource As TResource" />
      <MemberSignature Language="F#" Value="member this.Resource : 'Resource" Usage="Microsoft.Azure.Documents.Client.IResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3f31-103">応答で返されるリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="c3f31-103">Gets the resource returned in the response.</span></span>
            </summary>
        <value>
            <span data-ttu-id="c3f31-104">リソースは、応答で返されます。</span><span class="sxs-lookup"><span data-stu-id="c3f31-104">The resource returned in the response.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="c3f31-105">これは、Azure Cosmos DB サービスの目的をモックに公開されます。</span><span class="sxs-lookup"><span data-stu-id="c3f31-105">This is exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>