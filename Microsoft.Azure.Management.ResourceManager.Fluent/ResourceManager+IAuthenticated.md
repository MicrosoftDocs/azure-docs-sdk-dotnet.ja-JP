<Type Name="ResourceManager+IAuthenticated" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManager+IAuthenticated">
  <TypeSignature Language="C#" Value="public interface ResourceManager.IAuthenticated" />
  <TypeSignature Language="ILAsm" Value=".class nested public interface auto ansi abstract ResourceManager/IAuthenticated" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManager.IAuthenticated" />
  <TypeSignature Language="VB.NET" Value="Public Interface ResourceManager.IAuthenticated" />
  <TypeSignature Language="F#" Value="type ResourceManager.IAuthenticated = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="ca5f5-101">リソース管理 API のエントリを公開するインターフェイスは、サブスクリプションでその作業を指します。</span><span class="sxs-lookup"><span data-stu-id="ca5f5-101">The interface exposing resource management API entry points that work across subscriptions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Subscriptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.ISubscriptions Subscriptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.ISubscriptions Subscriptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManager.IAuthenticated.Subscriptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscriptions As ISubscriptions" />
      <MemberSignature Language="F#" Value="member this.Subscriptions : Microsoft.Azure.Management.ResourceManager.Fluent.ISubscriptions" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManager.IAuthenticated.Subscriptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.ISubscriptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca5f5-102">サブスクリプション管理 API へのエントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="ca5f5-102">Gets the entry point to subscription management API.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenants">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.ITenants Tenants { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.ITenants Tenants" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManager.IAuthenticated.Tenants" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tenants As ITenants" />
      <MemberSignature Language="F#" Value="member this.Tenants : Microsoft.Azure.Management.ResourceManager.Fluent.ITenants" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManager.IAuthenticated.Tenants" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.ITenants</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca5f5-103">テナント管理 API へのエントリ ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="ca5f5-103">Gets the entry point to tenant management API.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager WithSubscription (string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager WithSubscription(string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceManager.IAuthenticated.WithSubscription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubscription (subscriptionId As String) As IResourceManager" />
      <MemberSignature Language="F#" Value="abstract member WithSubscription : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager" Usage="iAuthenticated.WithSubscription subscriptionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="subscriptionId"><span data-ttu-id="ca5f5-104">サブスクリプションの UUID</span><span class="sxs-lookup"><span data-stu-id="ca5f5-104">The subscription UUID</span></span></param>
        <summary>
            <span data-ttu-id="ca5f5-105">サブスクリプションで使用できるリソースの管理 API エントリ ポイントを公開するサブスクリプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="ca5f5-105">Specifies a subscription to expose resource management API entry points that work in a subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="ca5f5-106">IResourceManager、サブスクリプションで動作するエントリ ポイント</span><span class="sxs-lookup"><span data-stu-id="ca5f5-106">The IResourceManager, the entry point that works in a subscription</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>