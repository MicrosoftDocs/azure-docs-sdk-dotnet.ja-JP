<Type Name="IFeatures" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.IFeatures">
  <TypeSignature Language="C#" Value="public interface IFeatures : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFeatures implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.IFeatures" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFeatures&#xA;Implements ISupportsListing(Of IFeature)" />
  <TypeSignature Language="F#" Value="type IFeatures = interface&#xA;    interface ISupportsListing&lt;IFeature&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1715c-101">機能管理 API へのエントリ ポイントです。</span><span class="sxs-lookup"><span data-stu-id="1715c-101">Entry point to features management API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IFeature Register (string resourceProviderNamespace, string featureName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.IFeature Register(string resourceProviderNamespace, string featureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IFeatures.Register(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Register (resourceProviderNamespace As String, featureName As String) As IFeature" />
      <MemberSignature Language="F#" Value="abstract member Register : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.IFeature" Usage="iFeatures.Register (resourceProviderNamespace, featureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IFeature</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceProviderNamespace"><span data-ttu-id="1715c-102">リソース プロバイダーの名前空間</span><span class="sxs-lookup"><span data-stu-id="1715c-102">the namespace of resource provider</span></span></param>
        <param name="featureName"><span data-ttu-id="1715c-103">機能の名前</span><span class="sxs-lookup"><span data-stu-id="1715c-103">the name of the feature</span></span></param>
        <summary>
            <span data-ttu-id="1715c-104">リソース プロバイダーの機能を登録します。</span><span class="sxs-lookup"><span data-stu-id="1715c-104">Registers a feature in a resource provider.</span></span>
            </summary>
        <returns><span data-ttu-id="1715c-105">作成されたクライアント側機能を変更できないオブジェクト</span><span class="sxs-lookup"><span data-stu-id="1715c-105">the immutable client-side feature object created</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt; RegisterAsync (string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt; RegisterAsync(string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IFeatures.RegisterAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegisterAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;" Usage="iFeatures.RegisterAsync (resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceProviderNamespace"><span data-ttu-id="1715c-106">リソース プロバイダーの名前空間</span><span class="sxs-lookup"><span data-stu-id="1715c-106">the namespace of resource provider</span></span></param>
        <param name="featureName"><span data-ttu-id="1715c-107">featureName 機能の名前</span><span class="sxs-lookup"><span data-stu-id="1715c-107">featureName the name of the feature</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="1715c-108">リソース プロバイダーの機能を登録します。</span><span class="sxs-lookup"><span data-stu-id="1715c-108">Registers a feature in a resource provider.</span></span>
            </summary>
        <returns><span data-ttu-id="1715c-109">作成されたクライアント側機能を変更できないオブジェクト</span><span class="sxs-lookup"><span data-stu-id="1715c-109">the immutable client-side feature object created</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>