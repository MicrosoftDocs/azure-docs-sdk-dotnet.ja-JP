<Type Name="ICdnProfile" FullName="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile">
  <TypeSignature Language="C#" Value="public interface ICdnProfile : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnManager,Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICdnProfile implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnManager, class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICdnProfile&#xA;Implements IGroupableResource(Of ICdnManager, ProfileInner), IHasInner(Of ProfileInner), IHasManager(Of ICdnManager), IRefreshable(Of ICdnProfile), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ICdnProfile = interface&#xA;    interface IGroupableResource&lt;ICdnManager, ProfileInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;ICdnManager&gt;&#xA;    interface IHasInner&lt;ProfileInner&gt;&#xA;    interface IRefreshable&lt;ICdnProfile&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnManager,Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure CDN のプロファイルの変更できないクライアント側表現。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckEndpointNameAvailability">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult CheckEndpointNameAvailability (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult CheckEndpointNameAvailability(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.CheckEndpointNameAvailability(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckEndpointNameAvailability (name As String) As CheckNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="abstract member CheckEndpointNameAvailability : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult" Usage="iCdnProfile.CheckEndpointNameAvailability name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">検証するエンドポイント リソースの名前。</param>
        <summary>
            CDN エンドポイントを作成せずには、エンドポイント名の可用性を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>正常終了した場合の結果。</return>
      </Docs>
    </Member>
    <Member MemberName="CheckEndpointNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult&gt; CheckEndpointNameAvailabilityAsync (string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult&gt; CheckEndpointNameAvailabilityAsync(string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.CheckEndpointNameAvailabilityAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckEndpointNameAvailabilityAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult&gt;" Usage="iCdnProfile.CheckEndpointNameAvailabilityAsync (name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CheckNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">検証するエンドポイント リソースの名前。</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            CDN エンドポイントを非同期に作成しなくても、エンドポイントの名前の可用性を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>正常終了した場合、結果の観測可能なオブジェクトです。</return>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt; Endpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoints As IReadOnlyDictionary(Of String, ICdnEndpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            名前によってインデックス付けされた CDN マネージャーのプロファイルのエンドポイントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateSsoUri">
      <MemberSignature Language="C#" Value="public string GenerateSsoUri ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GenerateSsoUri() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.GenerateSsoUri" />
      <MemberSignature Language="VB.NET" Value="Public Function GenerateSsoUri () As String" />
      <MemberSignature Language="F#" Value="abstract member GenerateSsoUri : unit -&gt; string" Usage="iCdnProfile.GenerateSsoUri " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            高度な管理タスクのために使用される、CDN 補助ポータルにサインインに使用される動的 SSO URI を生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>URI を使用するサード パーティの web ポータルにログインします。</return>
      </Docs>
    </Member>
    <Member MemberName="GenerateSsoUriAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GenerateSsoUriAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GenerateSsoUriAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.GenerateSsoUriAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GenerateSsoUriAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iCdnProfile.GenerateSsoUriAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            SSO の URI の高度な管理タスクに使用する CDN 補助ポータルにサインインするために使用する動的なを非同期に生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>使用される URI を監視可能なサード パーティの web ポータルにログインします。</return>
      </Docs>
    </Member>
    <Member MemberName="IsPremiumVerizon">
      <MemberSignature Language="C#" Value="public bool IsPremiumVerizon { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPremiumVerizon" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.IsPremiumVerizon" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPremiumVerizon As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPremiumVerizon : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.IsPremiumVerizon" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            CDN プロファイルの SKU は、Premium Verizon、偽の場合は true を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt; ListResourceUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt; ListResourceUsage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ListResourceUsage" />
      <MemberSignature Language="VB.NET" Value="Public Function ListResourceUsage () As IEnumerable(Of ResourceUsage)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsage : unit -&gt; seq&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt;" Usage="iCdnProfile.ListResourceUsage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>クォータと現在の CDN プロファイルでエンドポイントの実際の使用法です。</return>
      </Docs>
    </Member>
    <Member MemberName="LoadEndpointContent">
      <MemberSignature Language="C#" Value="public void LoadEndpointContent (string endpointName, System.Collections.Generic.ISet&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void LoadEndpointContent(string endpointName, class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.LoadEndpointContent(System.String,System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub LoadEndpointContent (endpointName As String, contentPaths As ISet(Of String))" />
      <MemberSignature Language="F#" Value="abstract member LoadEndpointContent : string * System.Collections.Generic.ISet&lt;string&gt; -&gt; unit" Usage="iCdnProfile.LoadEndpointContent (endpointName, contentPaths)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadEndpointContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task LoadEndpointContentAsync (string endpointName, System.Collections.Generic.ISet&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task LoadEndpointContentAsync(string endpointName, class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.LoadEndpointContentAsync(System.String,System.Collections.Generic.ISet{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadEndpointContentAsync : string * System.Collections.Generic.ISet&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnProfile.LoadEndpointContentAsync (endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeEndpointContent">
      <MemberSignature Language="C#" Value="public void PurgeEndpointContent (string endpointName, System.Collections.Generic.ISet&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PurgeEndpointContent(string endpointName, class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.PurgeEndpointContent(System.String,System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub PurgeEndpointContent (endpointName As String, contentPaths As ISet(Of String))" />
      <MemberSignature Language="F#" Value="abstract member PurgeEndpointContent : string * System.Collections.Generic.ISet&lt;string&gt; -&gt; unit" Usage="iCdnProfile.PurgeEndpointContent (endpointName, contentPaths)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeEndpointContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeEndpointContentAsync (string endpointName, System.Collections.Generic.ISet&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeEndpointContentAsync(string endpointName, class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.PurgeEndpointContentAsync(System.String,System.Collections.Generic.ISet{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeEndpointContentAsync : string * System.Collections.Generic.ISet&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnProfile.PurgeEndpointContentAsync (endpointName, contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName">To be added.</param>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceState">
      <MemberSignature Language="C#" Value="public string ResourceState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ResourceState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceState As String" />
      <MemberSignature Language="F#" Value="member this.ResourceState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ResourceState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            CDN プロファイル状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Cdn.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Cdn.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            CDN プロファイルの SKU を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartEndpoint">
      <MemberSignature Language="C#" Value="public void StartEndpoint (string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void StartEndpoint(string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.StartEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub StartEndpoint (endpointName As String)" />
      <MemberSignature Language="F#" Value="abstract member StartEndpoint : string -&gt; unit" Usage="iCdnProfile.StartEndpoint endpointName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointName">[プロファイル] で、エンドポイントの名前です。</param>
        <summary>
            停止された CDN エンドポイントを開始します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartEndpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartEndpointAsync (string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartEndpointAsync(string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.StartEndpointAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartEndpointAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnProfile.StartEndpointAsync (endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName">[プロファイル] で、エンドポイントの名前です。</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            停止された CDN エンドポイントを非同期的に起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="StopEndpoint">
      <MemberSignature Language="C#" Value="public void StopEndpoint (string endpointName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void StopEndpoint(string endpointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.StopEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub StopEndpoint (endpointName As String)" />
      <MemberSignature Language="F#" Value="abstract member StopEndpoint : string -&gt; unit" Usage="iCdnProfile.StopEndpoint endpointName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointName">[プロファイル] で、エンドポイントの名前です。</param>
        <summary>
            実行中の CDN エンドポイントを停止します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopEndpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopEndpointAsync (string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StopEndpointAsync(string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.StopEndpointAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopEndpointAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnProfile.StopEndpointAsync (endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName">[プロファイル] で、エンドポイントの名前です。</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            非同期的に実行中の CDN エンドポイントを停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="ValidateEndpointCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult ValidateEndpointCustomDomain (string endpointName, string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult ValidateEndpointCustomDomain(string endpointName, string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ValidateEndpointCustomDomain(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateEndpointCustomDomain (endpointName As String, hostName As String) As CustomDomainValidationResult" />
      <MemberSignature Language="F#" Value="abstract member ValidateEndpointCustomDomain : string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult" Usage="iCdnProfile.ValidateEndpointCustomDomain (endpointName, hostName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointName">[プロファイル] で、エンドポイントの名前です。</param>
        <param name="hostName">ドメイン名である必要があります、カスタム ドメインのホスト名。</param>
        <summary>
            現在のプロファイルで正しい CNAME を DNS にマッピングされていることを確認するカスタム ドメインのマップを検証します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>正常終了した場合は、オブジェクトを CustomDomainValidationResult です。</return>
      </Docs>
    </Member>
    <Member MemberName="ValidateEndpointCustomDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt; ValidateEndpointCustomDomainAsync (string endpointName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt; ValidateEndpointCustomDomainAsync(string endpointName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile.ValidateEndpointCustomDomainAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateEndpointCustomDomainAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt;" Usage="iCdnProfile.ValidateEndpointCustomDomainAsync (endpointName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="endpointName">[プロファイル] で、エンドポイントの名前です。</param>
        <param name="hostName">ドメイン名である必要があります、カスタム ドメインのホスト名。</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            マップ、正しい CNAME を DNS に現在のプロファイルで非同期的にことを確認するカスタム ドメインのマップを検証します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
        <return>正常終了した場合、CustomDomainValidationResult オブジェクトに観測可能なオブジェクトです。</return>
      </Docs>
    </Member>
  </Members>
</Type>