<Type Name="IResourceGroup" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup">
  <TypeSignature Language="C#" Value="public interface IResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroup.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IResourceGroup implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroup.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IResourceGroup&#xA;Implements IHasInner(Of ResourceGroupInner), IRefreshable(Of IResourceGroup), IResource, IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IResourceGroup = interface&#xA;    interface IIndexable&#xA;    interface IResource&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IRefreshable&lt;IResourceGroup&gt;&#xA;    interface IHasInner&lt;ResourceGroupInner&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroup.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="df381-101">Azure リソース グループの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="df381-101">An immutable client-side representation of an Azure resource group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExportTemplate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupExportResult ExportTemplate (Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupExportResult ExportTemplate(valuetype Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup.ExportTemplate(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExportTemplate (options As ResourceGroupExportTemplateOptions) As IResourceGroupExportResult" />
      <MemberSignature Language="F#" Value="abstract member ExportTemplate : Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupExportResult" Usage="iResourceGroup.ExportTemplate options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupExportResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="df381-102">エクスポート オプション</span><span class="sxs-lookup"><span data-stu-id="df381-102">options the export options</span></span></param>
        <summary>
            <span data-ttu-id="df381-103">テンプレートとして指定されたリソース グループをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="df381-103">Captures the specified resource group as a template.</span></span>
            </summary>
        <returns><span data-ttu-id="df381-104">エクスポートされたテンプレートの結果</span><span class="sxs-lookup"><span data-stu-id="df381-104">the exported template result</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupExportResult&gt; ExportTemplateAsync (Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions options, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupExportResult&gt; ExportTemplateAsync(valuetype Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions options, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupExportResult&gt;" Usage="iResourceGroup.ExportTemplateAsync (options, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupExportResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupExportTemplateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="df381-105">エクスポート オプション</span><span class="sxs-lookup"><span data-stu-id="df381-105">options the export options</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="df381-106">テンプレートとして指定されたリソース グループをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="df381-106">Captures the specified resource group as a template.</span></span>
            </summary>
        <returns><span data-ttu-id="df381-107">エクスポートされたテンプレートの結果</span><span class="sxs-lookup"><span data-stu-id="df381-107">the exported template result</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup.Name" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="df381-108">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="df381-108">the name of the resource group</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="df381-109">リソース グループのプロビジョニングの状態</span><span class="sxs-lookup"><span data-stu-id="df381-109">the provisioning state of the resource group</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>