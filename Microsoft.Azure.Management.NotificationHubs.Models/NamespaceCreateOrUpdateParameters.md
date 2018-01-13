<Type Name="NamespaceCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class NamespaceCreateOrUpdateParameters : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NamespaceCreateOrUpdateParameters extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class NamespaceCreateOrUpdateParameters&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NamespaceCreateOrUpdateParameters = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            CreateOrUpdate Namespace 操作に渡されるパラメーター。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NamespaceCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceCreateOrUpdateParameters (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, string namespaceCreateOrUpdateParametersName = null, string provisioningState = null, string region = null, string status = null, Nullable&lt;DateTime&gt; createdAt = null, string serviceBusEndpoint = null, string subscriptionId = null, string scaleUnit = null, Nullable&lt;bool&gt; enabled = null, Nullable&lt;bool&gt; critical = null, Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; namespaceType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, string namespaceCreateOrUpdateParametersName, string provisioningState, string region, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, string serviceBusEndpoint, string subscriptionId, string scaleUnit, valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;bool&gt; critical, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; namespaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters (location, id, name, type, tags, sku, namespaceCreateOrUpdateParametersName, provisioningState, region, status, createdAt, serviceBusEndpoint, subscriptionId, scaleUnit, enabled, critical, namespaceType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="namespaceCreateOrUpdateParametersName" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="region" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceBusEndpoint" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="scaleUnit" Type="System.String" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="critical" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="namespaceType" Type="System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt;" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所</param>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="tags">リソース タグ</param>
        <param name="sku">作成された名前空間の sku</param>
        <param name="namespaceCreateOrUpdateParametersName">名前空間の名前。</param>
        <param name="provisioningState">Namespace のプロビジョニング状態。</param>
        <param name="region">名前空間を作成する対象の地域を指定します。 次の値のいずれかのことができます: オーストラリア EastAustralia SoutheastCentral USEast USEast 米国 2West USNorth 中央 USSouth 中央 USEast AsiaSoutheast AsiaBrazil SouthJapan EastJapan WestNorth EuropeWest ヨーロッパ</param>
        <param name="status">名前空間の状態です。 これらの値: 1 のいずれかのことができます = Created/Active2 = Creating3 Suspended4 を = = 削除しています</param>
        <param name="createdAt">名前空間が作成された時刻。</param>
        <param name="serviceBusEndpoint">エンドポイントが NotificationHub 操作の実行に使用することができます。</param>
        <param name="subscriptionId">名前空間に関連付けられている Azure サブスクリプションの Id。</param>
        <param name="scaleUnit">名前空間が作成される ScaleUnit</param>
        <param name="enabled">名前空間が現在有効かどうか。</param>
        <param name="critical">かどうか、名前空間が"重大"に設定されます。</param>
        <param name="namespaceType">名前空間の種類。 使用可能な値が含まれます: 'メッセージング'、'NotificationHub'</param>
        <summary>
            NamespaceCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前空間が作成された時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Critical">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Critical { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Critical" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Critical" />
      <MemberSignature Language="VB.NET" Value="Public Property Critical As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Critical : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Critical" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.critical")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前空間が"重大"として設定されているかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前空間が現在有効になっているかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceCreateOrUpdateParametersName">
      <MemberSignature Language="C#" Value="public string NamespaceCreateOrUpdateParametersName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamespaceCreateOrUpdateParametersName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.NamespaceCreateOrUpdateParametersName" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceCreateOrUpdateParametersName As String" />
      <MemberSignature Language="F#" Value="member this.NamespaceCreateOrUpdateParametersName : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.NamespaceCreateOrUpdateParametersName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前空間の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; NamespaceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; NamespaceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.NamespaceType" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceType As Nullable(Of NamespaceType)" />
      <MemberSignature Language="F#" Value="member this.NamespaceType : Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.NamespaceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.namespaceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前空間の種類を設定します。 使用可能な値が含まれます: 'メッセージング'、'NotificationHub'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、Namespace のプロビジョニング状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public string Region { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Region" />
      <MemberSignature Language="VB.NET" Value="Public Property Region As String" />
      <MemberSignature Language="F#" Value="member this.Region : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.region")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、名前空間を作成する対象の地域を指定します。 次の値のいずれかのことができます: オーストラリア EastAustralia SoutheastCentral USEast USEast 米国 2West USNorth 中央 USSouth 中央 USEast AsiaSoutheast AsiaBrazil SouthJapan EastJapan WestNorth EuropeWest ヨーロッパ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleUnit">
      <MemberSignature Language="C#" Value="public string ScaleUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScaleUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ScaleUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleUnit As String" />
      <MemberSignature Language="F#" Value="member this.ScaleUnit : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ScaleUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleUnit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前空間が作成される scaleUnit を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public string ServiceBusEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ServiceBusEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または NotificationHub 操作の実行に使用できるエンドポイントを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前空間の状態を設定します。 これらの値: 1 のいずれかのことができます = Created/Active2 = Creating3 Suspended4 を = = 削除しています
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または名前空間に関連付けられている Azure サブスクリプションの Id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>