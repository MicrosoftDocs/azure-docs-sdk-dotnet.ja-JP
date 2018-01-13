<Type Name="StorageAccountInner" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner">
  <TypeSignature Language="C#" Value="public class StorageAccountInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type StorageAccountInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
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
      <MemberSignature Language="C#" Value="public StorageAccountInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StorageAccountInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; kind = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; provisioningState = null, Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints primaryEndpoints = null, string primaryLocation = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; statusOfPrimary = null, Nullable&lt;DateTime&gt; lastGeoFailoverTime = null, string secondaryLocation = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; statusOfSecondary = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints secondaryEndpoints = null, Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; provisioningState, class Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints primaryEndpoints, string primaryLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; statusOfPrimary, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastGeoFailoverTime, string secondaryLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; statusOfSecondary, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints secondaryEndpoints, class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Fluent.Models.Sku,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.Kind},System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState},Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints,System.String,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus},System.Nullable{System.DateTime},System.String,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus},System.Nullable{System.DateTime},Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain,Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints,Microsoft.Azure.Management.Storage.Fluent.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.Sku * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints * string * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain * Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints * Microsoft.Azure.Management.Storage.Fluent.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner (location, id, name, type, tags, sku, kind, provisioningState, primaryEndpoints, primaryLocation, statusOfPrimary, lastGeoFailoverTime, secondaryLocation, statusOfSecondary, creationTime, customDomain, secondaryEndpoints, encryption, accessTier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Sku" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt;" />
        <Parameter Name="primaryEndpoints" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints" />
        <Parameter Name="primaryLocation" Type="System.String" />
        <Parameter Name="statusOfPrimary" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;" />
        <Parameter Name="lastGeoFailoverTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="secondaryLocation" Type="System.String" />
        <Parameter Name="statusOfSecondary" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
        <Parameter Name="secondaryEndpoints" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="sku">SKU を取得します。</param>
        <param name="kind">種類を取得します。 使用可能な値が含まれます: 'Storage'、'BlobStorage'</param>
        <param name="provisioningState">操作が呼び出された時点でストレージ アカウントの状態を取得します。 使用可能な値が含まれます: '作成中'、'ResolvingDNS'、'成功'</param>
        <param name="primaryEndpoints">パブリック blob、キュー、またはテーブル オブジェクトを取得する際に使用する Url を取得します。 Standard_zrs の場合とが premium_lrs の場合のアカウントが、blob エンドポイントのみを返すことに注意してください。</param>
        <param name="primaryLocation">ストレージ アカウントのプライマリ データ センターの場所を取得します。</param>
        <param name="statusOfPrimary">ストレージ アカウントのプライマリの場所が使用可能または利用できないかどうかを示すステータスを取得します。 使用可能な値が含まれます使用可能'、'を使用できません'。</param>
        <param name="lastGeoFailoverTime">2 次拠点へのフェールオーバーの最新のインスタンスのタイムスタンプを取得します。 最新のタイムスタンプのみが保持されます。 フェールオーバー インスタンスなりました場合は、この要素は返されません。 Standard_GRS または Standard_RAGRS、accountType の場合にのみ使用できます。</param>
        <param name="secondaryLocation">ストレージ アカウントの地理的レプリケーション セカンダリの場所を取得します。 Standard_GRS または Standard_RAGRS、accountType の場合にのみ使用できます。</param>
        <param name="statusOfSecondary">ストレージ アカウントのセカンダリの場所が使用可能または利用できないかどうかを示すステータスを取得します。 SKU 名 Standard_GRS または Standard_RAGRS 場合にのみ使用できます。 使用可能な値が含まれます使用可能'、'を使用できません'。</param>
        <param name="creationTime">ストレージ アカウントの作成日時を UTC で取得します。</param>
        <param name="customDomain">このストレージ アカウントに割り当てられているユーザーにカスタム ドメインを取得します。</param>
        <param name="secondaryEndpoints">取得する際に、パブリック blob、キュー、またはテーブル オブジェクトのストレージ アカウントのセカンダリの場所から使用する Url を取得します。 SKU の名前が Standard_RAGRS 場合にのみ使用できます。</param>
        <param name="encryption">アカウントの暗号化の設定を取得します。 指定しない場合、アカウントは暗号化されません。</param>
        <param name="accessTier">ストレージ アカウントの場所の種類に必要な BlobStorage を = です。 アクセス層は、課金のために使用します。 使用可能な値が含まれます: 'ホット'、'ね'</param>
        <summary>
            StorageAccountInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このストレージ アカウントに割り当てられているユーザーにカスタム ドメインを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アカウントの暗号化の設定を取得します。 指定しない場合、アカウントは暗号化されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.Kind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            種類を取得します。 使用可能な値が含まれます: 'Storage'、'BlobStorage'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastGeoFailoverTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastGeoFailoverTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastGeoFailoverTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.LastGeoFailoverTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastGeoFailoverTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastGeoFailoverTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.LastGeoFailoverTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="PrimaryEndpoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints PrimaryEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints PrimaryEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.PrimaryEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryEndpoints As Endpoints" />
      <MemberSignature Language="F#" Value="member this.PrimaryEndpoints : Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.PrimaryEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.PrimaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryLocation : string" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.PrimaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints SecondaryEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints SecondaryEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.SecondaryEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryEndpoints As Endpoints" />
      <MemberSignature Language="F#" Value="member this.SecondaryEndpoints : Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.SecondaryEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Endpoints</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.SecondaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryLocation : string" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.SecondaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Sku</ReturnType>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; StatusOfPrimary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; StatusOfPrimary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.StatusOfPrimary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusOfPrimary As Nullable(Of AccountStatus)" />
      <MemberSignature Language="F#" Value="member this.StatusOfPrimary : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.StatusOfPrimary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusOfPrimary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントのプライマリの場所が使用可能または利用できないかどうかを示すステータスを取得します。 使用可能な値が含まれます使用可能'、'を使用できません'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusOfSecondary">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; StatusOfSecondary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt; StatusOfSecondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.StatusOfSecondary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusOfSecondary As Nullable(Of AccountStatus)" />
      <MemberSignature Language="F#" Value="member this.StatusOfSecondary : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.StatusOfSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusOfSecondary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントのセカンダリの場所が使用可能または利用できないかどうかを示すステータスを取得します。 SKU 名 Standard_GRS または Standard_RAGRS 場合にのみ使用できます。 使用可能な値が含まれます使用可能'、'を使用できません'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="storageAccountInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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