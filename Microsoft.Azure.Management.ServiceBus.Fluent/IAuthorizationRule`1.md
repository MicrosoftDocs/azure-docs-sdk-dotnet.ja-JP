<Type Name="IAuthorizationRule&lt;RuleT&gt;" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationRule&lt;RuleT&gt;">
  <TypeSignature Language="C#" Value="public interface IAuthorizationRule&lt;RuleT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;RuleT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAuthorizationRule`1&lt;RuleT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource`2&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager, class Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;!RuleT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationRule`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAuthorizationRule(Of RuleT)&#xA;Implements IGroupableResource(Of IServiceBusManager, SharedAccessAuthorizationRuleInner), IHasInner(Of SharedAccessAuthorizationRuleInner), IHasManager(Of IServiceBusManager), IIndependentChild(Of IServiceBusManager), IIndependentChildResource(Of IServiceBusManager, SharedAccessAuthorizationRuleInner), IRefreshable(Of RuleT)" />
  <TypeSignature Language="F#" Value="type IAuthorizationRule&lt;'RuleT&gt; = interface&#xA;    interface IIndependentChildResource&lt;IServiceBusManager, SharedAccessAuthorizationRuleInner&gt;&#xA;    interface IGroupableResource&lt;IServiceBusManager, SharedAccessAuthorizationRuleInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IServiceBusManager&gt;&#xA;    interface IHasInner&lt;SharedAccessAuthorizationRuleInner&gt;&#xA;    interface IIndependentChild&lt;IServiceBusManager&gt;&#xA;    interface IRefreshable&lt;'RuleT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="RuleT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager,Microsoft.Azure.Management.ServiceBus.Fluent.Models.SharedAccessAuthorizationRuleInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;RuleT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="RuleT"><span data-ttu-id="3c992-101">特定の規則の種類。</span><span class="sxs-lookup"><span data-stu-id="3c992-101">The specific rule type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="3c992-102">承認規則を表す型。</span><span class="sxs-lookup"><span data-stu-id="3c992-102">Type representing authorization rule.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="3c992-103">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="3c992-103">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys GetKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys GetKeys() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationRule`1.GetKeys" />
      <MemberSignature Language="VB.NET" Value="Public Function GetKeys () As IAuthorizationKeys" />
      <MemberSignature Language="F#" Value="abstract member GetKeys : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys" Usage="iAuthorizationRule.GetKeys " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3c992-104">プライマリ、セカンダリ キーと接続文字列。</span><span class="sxs-lookup"><span data-stu-id="3c992-104">The primary, secondary keys and connection strings.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys&gt; GetKeysAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys&gt; GetKeysAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationRule`1.GetKeysAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys&gt;" Usage="iAuthorizationRule.GetKeysAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3c992-105">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="3c992-105">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="3c992-106">プライマリ、セカンダリ キーを出力ストリームと接続文字列。</span><span class="sxs-lookup"><span data-stu-id="3c992-106">Stream that emits primary, secondary keys and connection strings.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys RegenerateKey (Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey policykey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys RegenerateKey(valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey policykey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationRule`1.RegenerateKey(Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKey : Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys" Usage="iAuthorizationRule.RegenerateKey policykey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policykey" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey" />
      </Parameters>
      <Docs>
        <param name="policykey"><span data-ttu-id="3c992-107">再生成するキー。</span><span class="sxs-lookup"><span data-stu-id="3c992-107">The key to regenerate.</span></span></param>
        <summary>
            <span data-ttu-id="3c992-108">プライマリまたはセカンダリ キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="3c992-108">Regenerates primary or secondary keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3c992-109">プライマリ、セカンダリ キーと接続文字列。</span><span class="sxs-lookup"><span data-stu-id="3c992-109">Primary, secondary keys and connection strings.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys&gt; RegenerateKeyAsync (Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey policykey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys&gt; RegenerateKeyAsync(valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey policykey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationRule`1.RegenerateKeyAsync(Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyAsync : Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys&gt;" Usage="iAuthorizationRule.RegenerateKeyAsync (policykey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policykey" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.Policykey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="policykey"><span data-ttu-id="3c992-110">再生成するキー。</span><span class="sxs-lookup"><span data-stu-id="3c992-110">The key to regenerate.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="3c992-111">プライマリまたはセカンダリ キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="3c992-111">Regenerates primary or secondary keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="3c992-112">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="3c992-112">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="3c992-113">プライマリ、セカンダリ キーを出力ストリームと接続文字列。</span><span class="sxs-lookup"><span data-stu-id="3c992-113">Stream that emits primary, secondary keys and connection strings.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt; Rights { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt; Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationRule`1.Rights" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Rights As IReadOnlyList(Of AccessRights)" />
      <MemberSignature Language="F#" Value="member this.Rights : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.IAuthorizationRule&lt;'RuleT&gt;.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c992-114">ルールに関連付けられている権限を取得します。</span><span class="sxs-lookup"><span data-stu-id="3c992-114">Gets rights associated with the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>