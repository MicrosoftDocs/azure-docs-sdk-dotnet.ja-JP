<Type Name="StorageAccount" FullName="Microsoft.Azure.Management.Storage.Models.StorageAccount">
  <TypeSignature Language="C#" Value="public class StorageAccount : Microsoft.Azure.Management.Storage.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccount extends Microsoft.Azure.Management.Storage.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.StorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type StorageAccount = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Storage.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ストレージ アカウントです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StorageAccount クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccount (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Models.Sku sku = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; kind = null, Microsoft.Azure.Management.Storage.Models.Identity identity = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.ProvisioningState&gt; provisioningState = null, Microsoft.Azure.Management.Storage.Models.Endpoints primaryEndpoints = null, string primaryLocation = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; statusOfPrimary = null, Nullable&lt;DateTime&gt; lastGeoFailoverTime = null, string secondaryLocation = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; statusOfSecondary = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Models.Endpoints secondaryEndpoints = null, Microsoft.Azure.Management.Storage.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier = null, Nullable&lt;bool&gt; enableHttpsTrafficOnly = null, Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Models.Sku sku, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; kind, class Microsoft.Azure.Management.Storage.Models.Identity identity, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.ProvisioningState&gt; provisioningState, class Microsoft.Azure.Management.Storage.Models.Endpoints primaryEndpoints, string primaryLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; statusOfPrimary, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastGeoFailoverTime, string secondaryLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; statusOfSecondary, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, class Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Models.Endpoints secondaryEndpoints, class Microsoft.Azure.Management.Storage.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier, valuetype System.Nullable`1&lt;bool&gt; enableHttpsTrafficOnly, class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccount.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Models.Sku,System.Nullable{Microsoft.Azure.Management.Storage.Models.Kind},Microsoft.Azure.Management.Storage.Models.Identity,System.Nullable{Microsoft.Azure.Management.Storage.Models.ProvisioningState},Microsoft.Azure.Management.Storage.Models.Endpoints,System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.AccountStatus},System.Nullable{System.DateTime},System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.AccountStatus},System.Nullable{System.DateTime},Microsoft.Azure.Management.Storage.Models.CustomDomain,Microsoft.Azure.Management.Storage.Models.Endpoints,Microsoft.Azure.Management.Storage.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Models.AccessTier},System.Nullable{System.Boolean},Microsoft.Azure.Management.Storage.Models.NetworkRuleSet)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.StorageAccount : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Models.Sku * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; * Microsoft.Azure.Management.Storage.Models.Identity * Nullable&lt;Microsoft.Azure.Management.Storage.Models.ProvisioningState&gt; * Microsoft.Azure.Management.Storage.Models.Endpoints * string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.Storage.Models.CustomDomain * Microsoft.Azure.Management.Storage.Models.Endpoints * Microsoft.Azure.Management.Storage.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Storage.Models.NetworkRuleSet -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccount" Usage="new Microsoft.Azure.Management.Storage.Models.StorageAccount (id, name, type, location, tags, sku, kind, identity, provisioningState, primaryEndpoints, primaryLocation, statusOfPrimary, lastGeoFailoverTime, secondaryLocation, statusOfSecondary, creationTime, customDomain, secondaryEndpoints, encryption, accessTier, enableHttpsTrafficOnly, networkRuleSet)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Models.Sku" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Storage.Models.Identity" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.ProvisioningState&gt;" />
        <Parameter Name="primaryEndpoints" Type="Microsoft.Azure.Management.Storage.Models.Endpoints" />
        <Parameter Name="primaryLocation" Type="System.String" />
        <Parameter Name="statusOfPrimary" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt;" />
        <Parameter Name="lastGeoFailoverTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="secondaryLocation" Type="System.String" />
        <Parameter Name="statusOfSecondary" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Models.CustomDomain" />
        <Parameter Name="secondaryEndpoints" Type="Microsoft.Azure.Management.Storage.Models.Endpoints" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;" />
        <Parameter Name="enableHttpsTrafficOnly" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkRuleSet" Type="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="location">リソースの場所</param>
        <param name="tags">リソースに割り当てられたタグ表示および (リソース グループ) の間でリソースをグループ化のために使用します。</param>
        <param name="sku">SKU を取得します。</param>
        <param name="kind">種類を取得します。 使用可能な値が含まれます: 'Storage'、'StorageV2'、'BlobStorage'</param>
        <param name="identity">リソースの id。</param>
        <param name="provisioningState">操作が呼び出された時点でストレージ アカウントの状態を取得します。 使用可能な値が含まれます: '作成中'、'ResolvingDNS'、'成功'</param>
        <param name="primaryEndpoints">パブリック blob、キュー、またはテーブル オブジェクトを取得する際に使用する Url を取得します。 Standard_zrs の場合とが premium_lrs の場合のアカウントが、blob エンドポイントのみを返すことに注意してください。</param>
        <param name="primaryLocation">ストレージ アカウントのプライマリ データ センターの場所を取得します。</param>
        <param name="statusOfPrimary">ストレージ アカウントのプライマリの場所が使用可能または利用できないかどうかを示すステータスを取得します。 使用可能な値が含まれます使用可能'、'使用できない'。</param>
        <param name="lastGeoFailoverTime">2 次拠点へのフェールオーバーの最新のインスタンスのタイムスタンプを取得します。 最新のタイムスタンプのみが保持されます。 フェールオーバー インスタンスなりました場合は、この要素は返されません。 Standard_GRS または Standard_RAGRS、accountType の場合にのみ使用できます。</param>
        <param name="secondaryLocation">ストレージ アカウントの地理的レプリケーション セカンダリの場所を取得します。 Standard_GRS または Standard_RAGRS、accountType の場合にのみ使用できます。</param>
        <param name="statusOfSecondary">ストレージ アカウントのセカンダリの場所が使用可能または利用できないかどうかを示すステータスを取得します。 SKU 名 Standard_GRS または Standard_RAGRS 場合にのみ使用できます。 使用可能な値が含まれます使用可能'、'使用できない'。</param>
        <param name="creationTime">ストレージ アカウントの作成日時を UTC で取得します。</param>
        <param name="customDomain">このストレージ アカウントに割り当てられているユーザーにカスタム ドメインを取得します。</param>
        <param name="secondaryEndpoints">取得する際に、パブリック blob、キュー、またはテーブル オブジェクトのストレージ アカウントのセカンダリの場所から使用する Url を取得します。 SKU の名前が Standard_RAGRS 場合にのみ使用できます。</param>
        <param name="encryption">アカウントの暗号化の設定を取得します。 指定しない場合、アカウントは暗号化されません。</param>
        <param name="accessTier">ストレージ アカウントの場所の種類に必要な BlobStorage を = です。 アクセス層は、課金のために使用します。 使用可能な値が含まれます: 'ホット'、'ね'</param>
        <param name="enableHttpsTrafficOnly">場合にのみストレージ サービスへの https トラフィックを許可を true に設定します。</param>
        <param name="networkRuleSet">ネットワーク ルール セット</param>
        <summary>
            StorageAccount クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントの種類での必要な取得 BlobStorage を = です。 アクセス層は、課金のために使用します。 使用可能な値が含まれます: 'ホット'、'ね'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントの作成日時を UTC で取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Models.CustomDomain" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このストレージ アカウントに割り当てられているユーザーにカスタム ドメインを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableHttpsTrafficOnly">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableHttpsTrafficOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableHttpsTrafficOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.EnableHttpsTrafficOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableHttpsTrafficOnly As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableHttpsTrafficOnly : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.EnableHttpsTrafficOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportsHttpsTrafficOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合に記憶域サービスのみ https トラフィックを許可するを取得または設定を true に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Encryption Encryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Models.Encryption" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アカウントの暗号化の設定を取得します。 指定しない場合、アカウントは暗号化されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Identity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Identity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As Identity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Storage.Models.Identity with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Identity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            種類を取得します。 使用可能な値が含まれます: 'Storage'、'StorageV2'、'BlobStorage'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastGeoFailoverTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastGeoFailoverTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastGeoFailoverTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.LastGeoFailoverTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastGeoFailoverTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastGeoFailoverTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.LastGeoFailoverTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastGeoFailoverTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            2 次拠点へのフェールオーバーの最新のインスタンスのタイムスタンプを取得します。 最新のタイムスタンプのみが保持されます。
            フェールオーバー インスタンスなりました場合は、この要素は返されません。 Standard_GRS または Standard_RAGRS、accountType の場合にのみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkRuleSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.NetworkRuleSet" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkRuleSet As NetworkRuleSet" />
      <MemberSignature Language="F#" Value="member this.NetworkRuleSet : Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.NetworkRuleSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAcls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.NetworkRuleSet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ネットワーク ルール セットの取得
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryEndpoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Endpoints PrimaryEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Endpoints PrimaryEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.PrimaryEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryEndpoints As Endpoints" />
      <MemberSignature Language="F#" Value="member this.PrimaryEndpoints : Microsoft.Azure.Management.Storage.Models.Endpoints" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.PrimaryEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Endpoints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パブリック blob、キュー、またはテーブル オブジェクトを取得する際に使用する Url を取得します。 Standard_zrs の場合とが premium_lrs の場合のアカウントが、blob エンドポイントのみを返すことに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryLocation">
      <MemberSignature Language="C#" Value="public string PrimaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.PrimaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryLocation : string" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.PrimaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントのプライマリ データ センターの場所を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Storage.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作が呼び出された時点でストレージ アカウントの状態を取得します。 使用可能な値が含まれます: '作成中'、'ResolvingDNS'、'成功'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryEndpoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Endpoints SecondaryEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Endpoints SecondaryEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.SecondaryEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryEndpoints As Endpoints" />
      <MemberSignature Language="F#" Value="member this.SecondaryEndpoints : Microsoft.Azure.Management.Storage.Models.Endpoints" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.SecondaryEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Endpoints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得する際に、パブリック blob、キュー、またはテーブル オブジェクトのストレージ アカウントのセカンダリの場所から使用する Url を取得します。 SKU の名前が Standard_RAGRS 場合にのみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryLocation">
      <MemberSignature Language="C#" Value="public string SecondaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.SecondaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryLocation : string" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.SecondaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントの地理的レプリケーション セカンダリの場所を取得します。 Standard_GRS または Standard_RAGRS、accountType の場合にのみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Models.Sku" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            SKU を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusOfPrimary">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; StatusOfPrimary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; StatusOfPrimary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.StatusOfPrimary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusOfPrimary As Nullable(Of AccountStatus)" />
      <MemberSignature Language="F#" Value="member this.StatusOfPrimary : Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt;" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.StatusOfPrimary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusOfPrimary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントのプライマリの場所が使用可能または利用できないかどうかを示すステータスを取得します。 使用可能な値が含まれます使用可能'、'使用できない'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusOfSecondary">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; StatusOfSecondary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccountStatus&gt; StatusOfSecondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccount.StatusOfSecondary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusOfSecondary As Nullable(Of AccountStatus)" />
      <MemberSignature Language="F#" Value="member this.StatusOfSecondary : Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt;" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccount.StatusOfSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusOfSecondary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントのセカンダリの場所が使用可能または利用できないかどうかを示すステータスを取得します。 SKU 名 Standard_GRS または Standard_RAGRS 場合にのみ使用できます。 使用可能な値が含まれます使用可能'、'使用できない'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>