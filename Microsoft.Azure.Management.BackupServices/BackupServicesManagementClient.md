<Type Name="BackupServicesManagementClient" FullName="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient">
  <TypeSignature Language="C#" Value="public class BackupServicesManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient&gt;, IDisposable, Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupServicesManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient&gt; implements class Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupServicesManagementClient&#xA;Inherits ServiceClient(Of BackupServicesManagementClient)&#xA;Implements IBackupServicesManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type BackupServicesManagementClient = class&#xA;    inherit ServiceClient&lt;BackupServicesManagementClient&gt;&#xA;    interface IBackupServicesManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupServicesManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupServicesManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            必須。 Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。 サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。
            </param>
        <summary>
            BackupServicesManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupServicesManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            Http クライアント
            </param>
        <summary>
            BackupServicesManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient (credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            必須。 Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。 サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。
            </param>
        <param name="httpClient">
            Http クライアント
            </param>
        <summary>
            BackupServicesManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient (credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="credentials">
            必須。 Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。 サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。
            </param>
        <param name="baseUri">
            省略可能。 すべてのクラウド サービス要求のベースとして使用する URI を取得します。
            </param>
        <summary>
            BackupServicesManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient (credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            必須。 Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。 サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。
            </param>
        <param name="baseUri">
            省略可能。 すべてのクラウド サービス要求のベースとして使用する URI を取得します。
            </param>
        <param name="httpClient">
            Http クライアント
            </param>
        <summary>
            BackupServicesManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.ApiVersion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            API のバージョンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackUp">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IBackUpOperations BackUp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IBackUpOperations BackUp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.BackUp" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property BackUp As IBackUpOperations" />
      <MemberSignature Language="F#" Value="member this.BackUp : Microsoft.Azure.Management.BackupServices.IBackUpOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.BackUp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.BackUp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IBackUpOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能のバックアップ操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            すべてのクラウド サービス要求のベースとして使用する URI を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of BackupServicesManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient&gt; -&gt; unit" Usage="backupServicesManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            複製する BackupServicesManagementClient のインスタンス
            </param>
        <summary>
            現在のインスタンスから別の BackupServicesManagementClient インスタンスにプロパティのクローンを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IContainerOperations Container { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IContainerOperations Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Container" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Container As IContainerOperations" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Management.BackupServices.IContainerOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Container" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Container</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IContainerOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能のコンテナーの操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。 サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CSMProtectionPolicy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations CSMProtectionPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations CSMProtectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.CSMProtectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property CSMProtectionPolicy As ICSMProtectionPolicyOperations" />
      <MemberSignature Language="F#" Value="member this.CSMProtectionPolicy : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.CSMProtectionPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.CSMProtectionPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の保護ポリシーの操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSource">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IDataSourceOperations DataSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IDataSourceOperations DataSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.DataSource" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property DataSource As IDataSourceOperations" />
      <MemberSignature Language="F#" Value="member this.DataSource : Microsoft.Azure.Management.BackupServices.IDataSourceOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.DataSource" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.DataSource</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IDataSourceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の操作をデータ ソースの定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Job">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IJobOperations Job { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IJobOperations Job" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Job" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Job As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.Job : Microsoft.Azure.Management.BackupServices.IJobOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Job" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Job</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure バックアップ用拡張子に対してジョブ操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.LongRunningOperationInitialTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または長時間実行される操作の初期タイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または長時間実行される操作の再試行タイムアウトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationStatus">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IOperationStatus OperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IOperationStatus OperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.OperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property OperationStatus As IOperationStatus" />
      <MemberSignature Language="F#" Value="member this.OperationStatus : Microsoft.Azure.Management.BackupServices.IOperationStatus" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.OperationStatus" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.OperationStatus</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IOperationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能のワークフロー操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectableObject">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations ProtectableObject { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations ProtectableObject" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.ProtectableObject" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ProtectableObject As IProtectableObjectOperations" />
      <MemberSignature Language="F#" Value="member this.ProtectableObject : Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.ProtectableObject" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.ProtectableObject</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の保護可能な ObjectOperation 操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPoint">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations RecoveryPoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations RecoveryPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.RecoveryPoint" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property RecoveryPoint As IRecoveryPointOperations" />
      <MemberSignature Language="F#" Value="member this.RecoveryPoint : Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.RecoveryPoint" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.RecoveryPoint</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の回復ポイントの操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IRestoreOperations Restore { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IRestoreOperations Restore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Restore" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Restore As IRestoreOperations" />
      <MemberSignature Language="F#" Value="member this.Restore : Microsoft.Azure.Management.BackupServices.IRestoreOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupServicesManagementClient.Restore" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupServicesManagementClient.Restore</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IRestoreOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Backup の拡張機能の復元操作の定義。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>