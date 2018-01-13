<Type Name="UsageDetail" FullName="Microsoft.Azure.Management.Consumption.Models.UsageDetail">
  <TypeSignature Language="C#" Value="public class UsageDetail : Microsoft.Azure.Management.Consumption.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageDetail extends Microsoft.Azure.Management.Consumption.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.Models.UsageDetail" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageDetail&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type UsageDetail = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Consumption.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            使用状況の詳細リソースの場合です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.UsageDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            UsageDetail クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageDetail (string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string billingPeriodId = null, string invoiceId = null, Nullable&lt;DateTime&gt; usageStart = null, Nullable&lt;DateTime&gt; usageEnd = null, string instanceName = null, string instanceId = null, string instanceLocation = null, string currency = null, Nullable&lt;decimal&gt; usageQuantity = null, Nullable&lt;decimal&gt; billableQuantity = null, Nullable&lt;decimal&gt; pretaxCost = null, Nullable&lt;bool&gt; isEstimated = null, string meterId = null, Microsoft.Azure.Management.Consumption.Models.MeterDetails meterDetails = null, string subscriptionGuid = null, string subscriptionName = null, string accountName = null, string departmentName = null, string product = null, string consumedService = null, string costCenter = null, string additionalProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string billingPeriodId, string invoiceId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; usageStart, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; usageEnd, string instanceName, string instanceId, string instanceLocation, string currency, valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; usageQuantity, valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; billableQuantity, valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; pretaxCost, valuetype System.Nullable`1&lt;bool&gt; isEstimated, string meterId, class Microsoft.Azure.Management.Consumption.Models.MeterDetails meterDetails, string subscriptionGuid, string subscriptionName, string accountName, string departmentName, string product, string consumedService, string costCenter, string additionalProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.UsageDetail.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.Nullable{System.Decimal},System.Nullable{System.Decimal},System.Nullable{System.Decimal},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.Consumption.Models.MeterDetails,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Consumption.Models.UsageDetail : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * string * Nullable&lt;decimal&gt; * Nullable&lt;decimal&gt; * Nullable&lt;decimal&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.Consumption.Models.MeterDetails * string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Consumption.Models.UsageDetail" Usage="new Microsoft.Azure.Management.Consumption.Models.UsageDetail (id, name, type, tags, billingPeriodId, invoiceId, usageStart, usageEnd, instanceName, instanceId, instanceLocation, currency, usageQuantity, billableQuantity, pretaxCost, isEstimated, meterId, meterDetails, subscriptionGuid, subscriptionName, accountName, departmentName, product, consumedService, costCenter, additionalProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="billingPeriodId" Type="System.String" />
        <Parameter Name="invoiceId" Type="System.String" />
        <Parameter Name="usageStart" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="usageEnd" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="instanceName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="instanceLocation" Type="System.String" />
        <Parameter Name="currency" Type="System.String" />
        <Parameter Name="usageQuantity" Type="System.Nullable&lt;System.Decimal&gt;" />
        <Parameter Name="billableQuantity" Type="System.Nullable&lt;System.Decimal&gt;" />
        <Parameter Name="pretaxCost" Type="System.Nullable&lt;System.Decimal&gt;" />
        <Parameter Name="isEstimated" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="meterId" Type="System.String" />
        <Parameter Name="meterDetails" Type="Microsoft.Azure.Management.Consumption.Models.MeterDetails" />
        <Parameter Name="subscriptionGuid" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="departmentName" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="consumedService" Type="System.String" />
        <Parameter Name="costCenter" Type="System.String" />
        <Parameter Name="additionalProperties" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="tags">リソース タグ。</param>
        <param name="billingPeriodId">使用法が属する、請求期間のリソースの id。</param>
        <param name="invoiceId">使用法に属している請求書リソースの id。</param>
        <param name="usageStart">使用率の詳細の日付時刻範囲の開始。</param>
        <param name="usageEnd">使用率の詳細の日付時刻範囲の終了。</param>
        <param name="instanceName">使用状況は、リソース インスタンスの名前。</param>
        <param name="instanceId">使用状況は、リソース インスタンスの uri。</param>
        <param name="instanceLocation">使用状況は、リソース インスタンスの場所です。</param>
        <param name="currency">これで、メーターが請求されます、たとえば、USD ISO 通貨です。</param>
        <param name="usageQuantity">使用状況の数量。</param>
        <param name="billableQuantity">課金対象の使用状況の数量。</param>
        <param name="pretaxCost">税引き前に、コストの量。</param>
        <param name="isEstimated">推定の使用法は変更されます。</param>
        <param name="meterId">メーターの id です。</param>
        <param name="meterDetails">メーターの詳細。 既定ではこの値を返さない、$ で指定されている場合を除きを展開します。</param>
        <param name="subscriptionGuid">サブスクリプションの guid です。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <param name="accountName">アカウント名です。</param>
        <param name="departmentName">部門の名前です。</param>
        <param name="product">製品名です。</param>
        <param name="consumedService">使用するサービスの名前です。</param>
        <param name="costCenter">部門、コスト センターの場合は、この部門のコスト センターが存在します。</param>
        <param name="additionalProperties">使用状況は、この項目の追加の詳細です。 既定ではこの値を返さない、$ で指定されている場合を除きを展開します。</param>
        <summary>
            UsageDetail クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アカウント名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public string AdditionalProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AdditionalProperties As String" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.additionalProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用状況は、この項目の追加の詳細を取得します。 既定ではこの値を返さない、$ で指定されている場合を除きを展開します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BillableQuantity">
      <MemberSignature Language="C#" Value="public Nullable&lt;decimal&gt; BillableQuantity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; BillableQuantity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.BillableQuantity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BillableQuantity As Nullable(Of Decimal)" />
      <MemberSignature Language="F#" Value="member this.BillableQuantity : Nullable&lt;decimal&gt;" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.BillableQuantity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.billableQuantity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Decimal&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            課金対象の使用数量を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BillingPeriodId">
      <MemberSignature Language="C#" Value="public string BillingPeriodId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BillingPeriodId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.BillingPeriodId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BillingPeriodId As String" />
      <MemberSignature Language="F#" Value="member this.BillingPeriodId : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.BillingPeriodId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.billingPeriodId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用法が属する課金期間リソースの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumedService">
      <MemberSignature Language="C#" Value="public string ConsumedService { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.ConsumedService" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsumedService As String" />
      <MemberSignature Language="F#" Value="member this.ConsumedService : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.ConsumedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.consumedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス名を使用してを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CostCenter">
      <MemberSignature Language="C#" Value="public string CostCenter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CostCenter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.CostCenter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CostCenter As String" />
      <MemberSignature Language="F#" Value="member this.CostCenter : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.CostCenter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.costCenter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            部門であるし、コスト センターが存在する場合は、この部門のコスト センターを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Currency">
      <MemberSignature Language="C#" Value="public string Currency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Currency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.Currency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Currency As String" />
      <MemberSignature Language="F#" Value="member this.Currency : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.Currency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メーターが請求されます、たとえば、USD 通貨の ISO を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DepartmentName">
      <MemberSignature Language="C#" Value="public string DepartmentName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DepartmentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.DepartmentName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DepartmentName As String" />
      <MemberSignature Language="F#" Value="member this.DepartmentName : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.DepartmentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.departmentName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            部門名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用状況は、リソース インスタンスの uri を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceLocation">
      <MemberSignature Language="C#" Value="public string InstanceLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.InstanceLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceLocation As String" />
      <MemberSignature Language="F#" Value="member this.InstanceLocation : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.InstanceLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用状況は、リソース インスタンスの位置を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceName">
      <MemberSignature Language="C#" Value="public string InstanceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.InstanceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceName As String" />
      <MemberSignature Language="F#" Value="member this.InstanceName : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.InstanceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用状況は、リソース インスタンスの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvoiceId">
      <MemberSignature Language="C#" Value="public string InvoiceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InvoiceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.InvoiceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InvoiceId As String" />
      <MemberSignature Language="F#" Value="member this.InvoiceId : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.InvoiceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.invoiceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用法に属している請求書リソースの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEstimated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsEstimated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsEstimated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.IsEstimated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsEstimated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsEstimated : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.IsEstimated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isEstimated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            変更の対象が推定の使用状況を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MeterDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Consumption.Models.MeterDetails MeterDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Consumption.Models.MeterDetails MeterDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.MeterDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MeterDetails As MeterDetails" />
      <MemberSignature Language="F#" Value="member this.MeterDetails : Microsoft.Azure.Management.Consumption.Models.MeterDetails" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.MeterDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.meterDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Consumption.Models.MeterDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メーターの詳細を取得します。 既定ではこの値を返さない、$ で指定されている場合を除きを展開します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MeterId">
      <MemberSignature Language="C#" Value="public string MeterId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MeterId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.MeterId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MeterId As String" />
      <MemberSignature Language="F#" Value="member this.MeterId : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.MeterId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.meterId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メーターの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PretaxCost">
      <MemberSignature Language="C#" Value="public Nullable&lt;decimal&gt; PretaxCost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; PretaxCost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.PretaxCost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PretaxCost As Nullable(Of Decimal)" />
      <MemberSignature Language="F#" Value="member this.PretaxCost : Nullable&lt;decimal&gt;" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.PretaxCost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pretaxCost")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Decimal&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            税引き前に、コストの量を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Product">
      <MemberSignature Language="C#" Value="public string Product { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Product" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.Product" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Product As String" />
      <MemberSignature Language="F#" Value="member this.Product : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.Product" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.product")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            製品名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionGuid">
      <MemberSignature Language="C#" Value="public string SubscriptionGuid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.SubscriptionGuid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionGuid As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionGuid : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.SubscriptionGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionGuid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サブスクリプション guid を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionName">
      <MemberSignature Language="C#" Value="public string SubscriptionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.SubscriptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionName As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionName : string" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.SubscriptionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サブスクリプションの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageEnd">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UsageEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UsageEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.UsageEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageEnd As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UsageEnd : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.UsageEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用率の詳細の日付時刻範囲の末尾を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageQuantity">
      <MemberSignature Language="C#" Value="public Nullable&lt;decimal&gt; UsageQuantity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; UsageQuantity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.UsageQuantity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageQuantity As Nullable(Of Decimal)" />
      <MemberSignature Language="F#" Value="member this.UsageQuantity : Nullable&lt;decimal&gt;" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.UsageQuantity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageQuantity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Decimal&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用状況の数量を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageStart">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UsageStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UsageStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.UsageDetail.UsageStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageStart As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UsageStart : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Consumption.Models.UsageDetail.UsageStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            使用率の詳細の日付時刻範囲の開始を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>