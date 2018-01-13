<Type Name="IAppServiceDomain" FullName="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain">
  <TypeSignature Language="C#" Value="public interface IAppServiceDomain : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceDomain implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceDomain&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, DomainInner), IHasInner(Of DomainInner), IHasManager(Of IAppServiceManager), IRefreshable(Of IAppServiceDomain), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IAppServiceDomain = interface&#xA;    interface IBeta&#xA;    interface IGroupableResource&lt;IAppServiceManager, DomainInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;DomainInner&gt;&#xA;    interface IRefreshable&lt;IAppServiceDomain&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            ドメインの変更できないクライアント側表現。
            Azure 内のドメインは、サード パーティ ドメイン プロバイダーから購入します。 Creatable.create() または Creatable.createAsync() を呼び出すことによって、AppServiceDomains.listAgreements(String) で表示されている契約に同意したことにします。
            </summary>
    <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AdminContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact AdminContact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact AdminContact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.AdminContact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AdminContact As Contact" />
      <MemberSignature Language="F#" Value="member this.AdminContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.AdminContact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            管理者の連絡先情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public bool AutoRenew { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoRenew As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.AutoRenew" />
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
            ドメインが自動的に更新された場合に true を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BillingContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact BillingContact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact BillingContact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.BillingContact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BillingContact As Contact" />
      <MemberSignature Language="F#" Value="member this.BillingContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.BillingContact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            課金連絡先情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Consent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent Consent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent Consent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.Consent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Consent As DomainPurchaseConsent" />
      <MemberSignature Language="F#" Value="member this.Consent : Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.Consent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            法的契約に同意を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public DateTime CreatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.CreatedTime" />
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
            ドメインの作成のタイムスタンプを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public DateTime ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ExpirationTime" />
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
            ドメインの有効期限タイムスタンプを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRenewedTime">
      <MemberSignature Language="C#" Value="public DateTime LastRenewedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastRenewedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.LastRenewedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRenewedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastRenewedTime : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.LastRenewedTime" />
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
            ドメインの最後の時間が書き換えられたときは、タイムスタンプを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; ManagedHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; ManagedHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ManagedHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedHostNames As IReadOnlyDictionary(Of String, HostName)" />
      <MemberSignature Language="F#" Value="member this.ManagedHostNames : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ManagedHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ドメインから派生し、Azure リソースに割り当てられているすべてのホスト名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.NameServers" />
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
            サーバーの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Privacy">
      <MemberSignature Language="C#" Value="public bool Privacy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Privacy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.Privacy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Privacy As Boolean" />
      <MemberSignature Language="F#" Value="member this.Privacy : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.Privacy" />
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
            このドメインのドメインのプライバシーが有効になっている場合は true を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadyForDnsRecordManagement">
      <MemberSignature Language="C#" Value="public bool ReadyForDnsRecordManagement { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReadyForDnsRecordManagement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ReadyForDnsRecordManagement" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadyForDnsRecordManagement As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReadyForDnsRecordManagement : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ReadyForDnsRecordManagement" />
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
            Azure Web アプリをこのドメインを割り当てることができる場合は true を取得します。 この値は、ドメインの登録状態がアクティブで、Azure へのプログラムによるアクセスでは、名前のサーバーでホストされている場合、true になります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrantContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact RegistrantContact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact RegistrantContact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.RegistrantContact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrantContact As Contact" />
      <MemberSignature Language="F#" Value="member this.RegistrantContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.RegistrantContact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            登録者連絡先情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus RegistrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrationStatus As DomainStatus" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.RegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ドメインの登録状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TechContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact TechContact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact TechContact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.TechContact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TechContact As Contact" />
      <MemberSignature Language="F#" Value="member this.TechContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.TechContact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            技術的な連絡先情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnership">
      <MemberSignature Language="C#" Value="public void VerifyDomainOwnership (string certificateOrderName, string domainVerificationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void VerifyDomainOwnership(string certificateOrderName, string domainVerificationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.VerifyDomainOwnership(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub VerifyDomainOwnership (certificateOrderName As String, domainVerificationToken As String)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnership : string * string -&gt; unit" Usage="iAppServiceDomain.VerifyDomainOwnership (certificateOrderName, domainVerificationToken)" />
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
            このドメインにバインドされている証明書の順序のドメインの所有権を確認します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task VerifyDomainOwnershipAsync (string certificateOrderName, string domainVerificationToken, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(string certificateOrderName, string domainVerificationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.VerifyDomainOwnershipAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnershipAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAppServiceDomain.VerifyDomainOwnershipAsync (certificateOrderName, domainVerificationToken, cancellationToken)" />
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
            このドメインにバインドされている証明書の順序のドメインの所有権を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>この呼び出しの遅延の計算の表現。</return>
      </Docs>
    </Member>
  </Members>
</Type>