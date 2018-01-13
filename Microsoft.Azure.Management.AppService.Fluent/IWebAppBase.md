<Type Name="IWebAppBase" FullName="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase">
  <TypeSignature Language="C#" Value="public interface IWebAppBase : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWebAppBase implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWebAppBase&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, SiteInner), IHasInner(Of SiteInner), IHasManager(Of IAppServiceManager)" />
  <TypeSignature Language="F#" Value="type IWebAppBase = interface&#xA;    interface IBeta&#xA;    interface IHasName&#xA;    interface IGroupableResource&lt;IAppServiceManager, SiteInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;SiteInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure Web アプリまたは展開のスロットの変更できないクライアント側表現。
            </summary>
    <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AlwaysOn">
      <MemberSignature Language="C#" Value="public bool AlwaysOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AlwaysOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AlwaysOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlwaysOn As Boolean" />
      <MemberSignature Language="F#" Value="member this.AlwaysOn : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AlwaysOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリは常にオン場合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplySlotConfigurations">
      <MemberSignature Language="C#" Value="public void ApplySlotConfigurations (string slotName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ApplySlotConfigurations(string slotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ApplySlotConfigurations(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ApplySlotConfigurations (slotName As String)" />
      <MemberSignature Language="F#" Value="abstract member ApplySlotConfigurations : string -&gt; unit" Usage="iWebAppBase.ApplySlotConfigurations slotName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="slotName">ターゲットのスロットから構成を適用します。</param>
        <summary>
            スロットに適用 (または固定) 現在のバージョンに指定されたスロットから構成されます。 これは、「プレビューでスワップ」に役立ちます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplySlotConfigurationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ApplySlotConfigurationsAsync (string slotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ApplySlotConfigurationsAsync(string slotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ApplySlotConfigurationsAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ApplySlotConfigurationsAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.ApplySlotConfigurationsAsync (slotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="slotName">ターゲットのスロットから構成を適用します。</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            スロットに適用 (または固定) 現在のバージョンに指定されたスロットから構成されます。 これは、「プレビューでスワップ」に役立ちます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlanId">
      <MemberSignature Language="C#" Value="public string AppServicePlanId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServicePlanId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AppServicePlanId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServicePlanId As String" />
      <MemberSignature Language="F#" Value="member this.AppServicePlanId : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AppServicePlanId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            App service プランのリソース ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoSwapSlotName">
      <MemberSignature Language="C#" Value="public string AutoSwapSlotName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoSwapSlotName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AutoSwapSlotName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoSwapSlotName As String" />
      <MemberSignature Language="F#" Value="member this.AutoSwapSlotName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AutoSwapSlotName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            自動スワップ スロット名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState AvailabilityState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState AvailabilityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AvailabilityState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityState As SiteAvailabilityState" />
      <MemberSignature Language="F#" Value="member this.AvailabilityState : Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AvailabilityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリの管理情報の可用性の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAffinityEnabled">
      <MemberSignature Language="C#" Value="public bool ClientAffinityEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ClientAffinityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ClientAffinityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientAffinityEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ClientAffinityEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ClientAffinityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合は、クライアントのアフィニティが有効になっているときに負荷が web アプリの複数のインスタンスの http 要求を分散します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertEnabled">
      <MemberSignature Language="C#" Value="public bool ClientCertEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ClientCertEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ClientCertEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientCertEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ClientCertEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ClientCertEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリのクライアント証明書が有効になっている場合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloningInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.CloningInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CloningInfo As CloningInfo" />
      <MemberSignature Language="F#" Value="member this.CloningInfo : Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.CloningInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            別の web アプリを複製するかどうかに関する情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSize">
      <MemberSignature Language="C#" Value="public int ContainerSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ContainerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ContainerSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ContainerSize : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ContainerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            関数のコンテナーのサイズを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDocuments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; DefaultDocuments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; DefaultDocuments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.DefaultDocuments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultDocuments As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DefaultDocuments : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.DefaultDocuments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            既定のドキュメントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultHostName">
      <MemberSignature Language="C#" Value="public string DefaultHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.DefaultHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultHostName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.DefaultHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリの既定のホスト名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deploy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebDeployment.Definition.IWithPackageUri Deploy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebDeployment.Definition.IWithPackageUri Deploy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Deploy" />
      <MemberSignature Language="VB.NET" Value="Public Function Deploy () As IWithPackageUri" />
      <MemberSignature Language="F#" Value="abstract member Deploy : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebDeployment.Definition.IWithPackageUri" Usage="iWebAppBase.Deploy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebDeployment.Definition.IWithPackageUri</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サイトが有効である場合は true を取得します。それ以外の場合は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; EnabledHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; EnabledHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.EnabledHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledHostNames As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.EnabledHostNames : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.EnabledHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリを有効になっているホスト名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewaySiteName">
      <MemberSignature Language="C#" Value="public string GatewaySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewaySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GatewaySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GatewaySiteName As String" />
      <MemberSignature Language="F#" Value="member this.GatewaySiteName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GatewaySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリに関連付けられたゲートウェイ アプリの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt; GetAppSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt; GetAppSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetAppSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAppSettings () As IReadOnlyDictionary(Of String, IAppSetting)" />
      <MemberSignature Language="F#" Value="abstract member GetAppSettings : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;" Usage="iWebAppBase.GetAppSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppSettingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;&gt; GetAppSettingsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;&gt; GetAppSettingsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetAppSettingsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAppSettingsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;&gt;" Usage="iWebAppBase.GetAppSettingsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication GetAuthenticationConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication GetAuthenticationConfig() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetAuthenticationConfig" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthenticationConfig () As IWebAppAuthentication" />
      <MemberSignature Language="F#" Value="abstract member GetAuthenticationConfig : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication" Usage="iWebAppBase.GetAuthenticationConfig " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationConfigAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication&gt; GetAuthenticationConfigAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication&gt; GetAuthenticationConfigAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetAuthenticationConfigAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthenticationConfigAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication&gt;" Usage="iWebAppBase.GetAuthenticationConfigAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionStrings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt; GetConnectionStrings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt; GetConnectionStrings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetConnectionStrings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConnectionStrings () As IReadOnlyDictionary(Of String, IConnectionString)" />
      <MemberSignature Language="F#" Value="abstract member GetConnectionStrings : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;" Usage="iWebAppBase.GetConnectionStrings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionStringsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;&gt; GetConnectionStringsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;&gt; GetConnectionStringsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetConnectionStringsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetConnectionStringsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;&gt;" Usage="iWebAppBase.GetConnectionStringsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHostNameBindings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt; GetHostNameBindings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt; GetHostNameBindings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetHostNameBindings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHostNameBindings () As IReadOnlyDictionary(Of String, IHostNameBinding)" />
      <MemberSignature Language="F#" Value="abstract member GetHostNameBindings : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;" Usage="iWebAppBase.GetHostNameBindings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ホスト名とホスト名のバインドからのマッピング。</return>
      </Docs>
    </Member>
    <Member MemberName="GetHostNameBindingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;&gt; GetHostNameBindingsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;&gt; GetHostNameBindingsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetHostNameBindingsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetHostNameBindingsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;&gt;" Usage="iWebAppBase.GetHostNameBindingsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ホスト名とホスト名のバインドからのマッピング。</return>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile GetPublishingProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile GetPublishingProfile() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetPublishingProfile" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPublishingProfile () As IPublishingProfile" />
      <MemberSignature Language="F#" Value="abstract member GetPublishingProfile : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile" Usage="iWebAppBase.GetPublishingProfile " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>URL と FTP または Git を使用したパブリッシュ用の資格情報。</return>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingProfileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile&gt; GetPublishingProfileAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile&gt; GetPublishingProfileAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetPublishingProfileAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPublishingProfileAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile&gt;" Usage="iWebAppBase.GetPublishingProfileAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>URL と FTP または Git を使用したパブリッシュ用の資格情報。</return>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl GetSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl GetSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSourceControl () As IWebAppSourceControl" />
      <MemberSignature Language="F#" Value="abstract member GetSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl" Usage="iWebAppBase.GetSourceControl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリのソース管理情報。</return>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl&gt; GetSourceControlAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl&gt; GetSourceControlAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetSourceControlAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSourceControlAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl&gt;" Usage="iWebAppBase.GetSourceControlAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリのソース管理情報。</return>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; HostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリに関連付けられているホスト名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNamesDisabled">
      <MemberSignature Language="C#" Value="public bool HostNamesDisabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HostNamesDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNamesDisabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNamesDisabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.HostNamesDisabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNamesDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得のパブリック ホスト名がある場合に、web アプリが無効になります。
            場合、アプリを true に設定するだけ API 管理プロセスを使用してアクセスできます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameSslStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNameSslStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNameSslStates As IReadOnlyDictionary(Of String, HostNameSslState)" />
      <MemberSignature Language="F#" Value="member this.HostNameSslStates : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNameSslStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            SSL の状態を使用して、サイトのホスト名の SSL バインドの管理の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultContainer">
      <MemberSignature Language="C#" Value="public bool IsDefaultContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDefaultContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.IsDefaultContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultContainer As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDefaultContainer : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.IsDefaultContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得サイトは、既定のコンテナーです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPremiumApp">
      <MemberSignature Language="C#" Value="public bool IsPremiumApp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPremiumApp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.IsPremiumApp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPremiumApp As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPremiumApp : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.IsPremiumApp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Premium アプリとして web アプリが展開されたかどうかを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaContainer">
      <MemberSignature Language="C#" Value="public string JavaContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JavaContainer As String" />
      <MemberSignature Language="F#" Value="member this.JavaContainer : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Java コンテナーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaContainerVersion">
      <MemberSignature Language="C#" Value="public string JavaContainerVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaContainerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaContainerVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JavaContainerVersion As String" />
      <MemberSignature Language="F#" Value="member this.JavaContainerVersion : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaContainerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンテナーの Java バージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.JavaVersion JavaVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.JavaVersion JavaVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JavaVersion As JavaVersion" />
      <MemberSignature Language="F#" Value="member this.JavaVersion : Microsoft.Azure.Management.AppService.Fluent.JavaVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.JavaVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Java バージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリは UTC に変更された最終時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxFxVersion">
      <MemberSignature Language="C#" Value="public string LinuxFxVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinuxFxVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.LinuxFxVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinuxFxVersion As String" />
      <MemberSignature Language="F#" Value="member this.LinuxFxVersion : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.LinuxFxVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedPipelineMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode ManagedPipelineMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode ManagedPipelineMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ManagedPipelineMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedPipelineMode As ManagedPipelineMode" />
      <MemberSignature Language="F#" Value="member this.ManagedPipelineMode : Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ManagedPipelineMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            マネージ パイプライン モードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicroService">
      <MemberSignature Language="C#" Value="public string MicroService { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicroService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.MicroService" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MicroService As String" />
      <MemberSignature Language="F#" Value="member this.MicroService : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.MicroService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            マイクロ サービスの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetFrameworkVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion NetFrameworkVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion NetFrameworkVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.NetFrameworkVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetFrameworkVersion As NetFrameworkVersion" />
      <MemberSignature Language="F#" Value="member this.NetFrameworkVersion : Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.NetFrameworkVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            .NET Framework のバージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeVersion">
      <MemberSignature Language="C#" Value="public string NodeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.NodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.NodeVersion : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.NodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Node.JS のバージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatingSystem">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.OperatingSystem OperatingSystem { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.OperatingSystem OperatingSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.OperatingSystem" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperatingSystem As OperatingSystem" />
      <MemberSignature Language="F#" Value="member this.OperatingSystem : Microsoft.Azure.Management.AppService.Fluent.OperatingSystem" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.OperatingSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.OperatingSystem</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリが実行されているオペレーティング システムを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIPAddresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; OutboundIPAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; OutboundIPAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.OutboundIPAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundIPAddresses As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.OutboundIPAddresses : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.OutboundIPAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この web アプリが発信接続に使用する IP アドレスの一覧を取得します。 これらは、この web アプリがアクセスするデータベースのファイアウォール ルールを構成するときに使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PhpVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.PhpVersion PhpVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.PhpVersion PhpVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PhpVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PhpVersion As PhpVersion" />
      <MemberSignature Language="F#" Value="member this.PhpVersion : Microsoft.Azure.Management.AppService.Fluent.PhpVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PhpVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.PhpVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            PHP のバージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformArchitecture">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture PlatformArchitecture { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture PlatformArchitecture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PlatformArchitecture" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PlatformArchitecture As PlatformArchitecture" />
      <MemberSignature Language="F#" Value="member this.PlatformArchitecture : Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PlatformArchitecture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            32 ビット (x86) または 64 ビット (x64) プラットフォームのアーキテクチャを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.PythonVersion PythonVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.PythonVersion PythonVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PythonVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PythonVersion As PythonVersion" />
      <MemberSignature Language="F#" Value="member this.PythonVersion : Microsoft.Azure.Management.AppService.Fluent.PythonVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PythonVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.PythonVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Python のバージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteDebuggingEnabled">
      <MemberSignature Language="C#" Value="public bool RemoteDebuggingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoteDebuggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RemoteDebuggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteDebuggingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoteDebuggingEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RemoteDebuggingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リモート eebugging が有効になっている場合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteDebuggingVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion RemoteDebuggingVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion RemoteDebuggingVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RemoteDebuggingVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteDebuggingVersion As RemoteVisualStudioVersion" />
      <MemberSignature Language="F#" Value="member this.RemoteDebuggingVersion : Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RemoteDebuggingVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リモート デバッグ バージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositorySiteName">
      <MemberSignature Language="C#" Value="public string RepositorySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositorySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RepositorySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositorySiteName As String" />
      <MemberSignature Language="F#" Value="member this.RepositorySiteName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RepositorySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リポジトリ サイトの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSlotConfigurations">
      <MemberSignature Language="C#" Value="public void ResetSlotConfigurations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ResetSlotConfigurations() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ResetSlotConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetSlotConfigurations ()" />
      <MemberSignature Language="F#" Value="abstract member ResetSlotConfigurations : unit -&gt; unit" Usage="iWebAppBase.ResetSlotConfigurations " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            スロットをその元の設定にリセットします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSlotConfigurationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetSlotConfigurationsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResetSlotConfigurationsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ResetSlotConfigurationsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetSlotConfigurationsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.ResetSlotConfigurationsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            スロットをその元の設定にリセットします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public void Restart ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Restart() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Restart" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restart ()" />
      <MemberSignature Language="F#" Value="abstract member Restart : unit -&gt; unit" Usage="iWebAppBase.Restart " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Web アプリまたは配置スロットを再起動します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RestartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.RestartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Web アプリまたは配置スロットを再起動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="ScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public bool ScmSiteAlsoStopped { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ScmSiteAlsoStopped" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ScmSiteAlsoStopped" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScmSiteAlsoStopped As Boolean" />
      <MemberSignature Language="F#" Value="member this.ScmSiteAlsoStopped : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ScmSiteAlsoStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリが停止したときに、SCM (KUDU) サイトを停止するかどうかを取得します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iWebAppBase.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Web アプリまたは配置スロットを開始します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Web アプリまたは配置スロットを開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリの状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public void Stop ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Stop() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Stop" />
      <MemberSignature Language="VB.NET" Value="Public Sub Stop ()" />
      <MemberSignature Language="F#" Value="abstract member Stop : unit -&gt; unit" Usage="iWebAppBase.Stop " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Web アプリまたは配置スロットを停止します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StopAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.StopAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.StopAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Web アプリまたは配置スロットを停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="Swap">
      <MemberSignature Language="C#" Value="public void Swap (string slotName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Swap(string slotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Swap(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Swap (slotName As String)" />
      <MemberSignature Language="F#" Value="abstract member Swap : string -&gt; unit" Usage="iWebAppBase.Swap slotName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="slotName">
            スワップのターゲット スロットです。 運用スロットに '運用' を使用します。
            </param>
        <summary>
            現在実行されているアプリは web アプリ/、指定されたスロットで実行されているアプリのスロットをスワップします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SwapAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SwapAsync (string slotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SwapAsync(string slotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.SwapAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SwapAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.SwapAsync (slotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="slotName">
            スワップのターゲット スロットです。 運用スロットに '運用' を使用します。
            </param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            現在実行されているアプリは web アプリ/、指定されたスロットで実行されているアプリのスロットをスワップします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="TargetSwapSlot">
      <MemberSignature Language="C#" Value="public string TargetSwapSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSwapSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.TargetSwapSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetSwapSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSwapSlot : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.TargetSwapSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアプリがスワップしてスロットを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; TrafficManagerHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; TrafficManagerHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.TrafficManagerHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerHostNames As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerHostNames : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.TrafficManagerHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web アプリに関連付けられている Azure Traffic manager のホスト名の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.UsageState UsageState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UsageState UsageState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.UsageState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageState As UsageState" />
      <MemberSignature Language="F#" Value="member this.UsageState : Microsoft.Azure.Management.AppService.Fluent.Models.UsageState" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.UsageState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.UsageState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得の状態は web アプリがそのクォータ使用率を超えたかどうかを示すです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnership">
      <MemberSignature Language="C#" Value="public void VerifyDomainOwnership (string certificateOrderName, string domainVerificationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void VerifyDomainOwnership(string certificateOrderName, string domainVerificationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.VerifyDomainOwnership(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub VerifyDomainOwnership (certificateOrderName As String, domainVerificationToken As String)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnership : string * string -&gt; unit" Usage="iWebAppBase.VerifyDomainOwnership (certificateOrderName, domainVerificationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="domainVerificationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateOrderName">証明書の順序の名前。</param>
        <param name="domainVerificationToken">証明書の順序のドメインの検証トークンです。</param>
        <summary>
            ドメインのホスト名を確認し、証明書の順序のドメインの所有権がこの web アプリにバインドされていることを確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task VerifyDomainOwnershipAsync (string certificateOrderName, string domainVerificationToken, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(string certificateOrderName, string domainVerificationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.VerifyDomainOwnershipAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnershipAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.VerifyDomainOwnershipAsync (certificateOrderName, domainVerificationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="domainVerificationToken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="certificateOrderName">証明書の順序の名前。</param>
        <param name="domainVerificationToken">証明書の順序のドメインの検証トークンです。</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            ドメインのホスト名を確認し、証明書の順序のドメインの所有権がこの web アプリにバインドされていることを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
    <Member MemberName="WebSocketsEnabled">
      <MemberSignature Language="C#" Value="public bool WebSocketsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool WebSocketsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.WebSocketsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebSocketsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.WebSocketsEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.WebSocketsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Web ソケットが有効になっている場合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>