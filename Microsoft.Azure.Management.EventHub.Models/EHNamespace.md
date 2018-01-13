<Type Name="EHNamespace" FullName="Microsoft.Azure.Management.EventHub.Models.EHNamespace">
  <TypeSignature Language="C#" Value="public class EHNamespace : Microsoft.Azure.Management.EventHub.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EHNamespace extends Microsoft.Azure.Management.EventHub.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.EHNamespace" />
  <TypeSignature Language="VB.NET" Value="Public Class EHNamespace&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type EHNamespace = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventHub.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            リストまたは取得操作の 1 つの Namespace 項目
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EHNamespace ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.EHNamespace.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            EHNamespace クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EHNamespace (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.EventHub.Models.Sku sku = null, string provisioningState = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, string serviceBusEndpoint = null, string metricId = null, Nullable&lt;bool&gt; isAutoInflateEnabled = null, Nullable&lt;int&gt; maximumThroughputUnits = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.EventHub.Models.Sku sku, string provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, string serviceBusEndpoint, string metricId, valuetype System.Nullable`1&lt;bool&gt; isAutoInflateEnabled, valuetype System.Nullable`1&lt;int32&gt; maximumThroughputUnits) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.EHNamespace.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.EventHub.Models.Sku,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.EHNamespace : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.EventHub.Models.Sku * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.EventHub.Models.EHNamespace" Usage="new Microsoft.Azure.Management.EventHub.Models.EHNamespace (id, name, type, location, tags, sku, provisioningState, createdAt, updatedAt, serviceBusEndpoint, metricId, isAutoInflateEnabled, maximumThroughputUnits)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.EventHub.Models.Sku" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceBusEndpoint" Type="System.String" />
        <Parameter Name="metricId" Type="System.String" />
        <Parameter Name="isAutoInflateEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="maximumThroughputUnits" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="location">リソースの場所</param>
        <param name="tags">リソース タグ</param>
        <param name="sku">Sku のリソースのプロパティ</param>
        <param name="provisioningState">Namespace のプロビジョニング状態。</param>
        <param name="createdAt">Namespace が作成された時刻。</param>
        <param name="updatedAt">Namespace が更新された時刻。</param>
        <param name="serviceBusEndpoint">エンドポイントが Service Bus 操作の実行に使用することができます。</param>
        <param name="metricId">Azure インサイト メトリックの識別子。</param>
        <param name="isAutoInflateEnabled">Eventhub の名前空間の AutoInflate が有効になっているかどうかを示す値です。</param>
        <param name="maximumThroughputUnits">AutoInflate が有効にすると、スループット単位の上限値は 0 ~ 20 スループット単位内でする必要があります。 (場合は '0' AutoInflateEnabled = true)</param>
        <summary>
            EHNamespace クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
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
            Namespace が作成された日時を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAutoInflateEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAutoInflateEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAutoInflateEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.IsAutoInflateEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAutoInflateEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAutoInflateEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.IsAutoInflateEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isAutoInflateEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または eventhub の名前空間の AutoInflate が有効になっているかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumThroughputUnits">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumThroughputUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumThroughputUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.MaximumThroughputUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumThroughputUnits As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumThroughputUnits : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.MaximumThroughputUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximumThroughputUnits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定上限 AutoInflate が有効にすると、スループット単位の制限値は 0 ~ 20 スループット単位内にする必要があります。 (場合は '0' AutoInflateEnabled = true)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricId">
      <MemberSignature Language="C#" Value="public string MetricId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.MetricId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricId As String" />
      <MemberSignature Language="F#" Value="member this.MetricId : string" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.MetricId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metricId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure インサイト メトリックの識別子を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
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
            取得のプロビジョニング状態、Namespace です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public string ServiceBusEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceBusEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : string" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.ServiceBusEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
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
            Service Bus 操作の実行に使用できるエンドポイントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventHub.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.EventHub.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.EventHub.Models.Sku with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または sku のリソースのプロパティを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.EHNamespace.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.EHNamespace.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Namespace が更新された時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.EHNamespace.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="eHNamespace.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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