<Type Name="ValidateRequest" FullName="Microsoft.Azure.Management.WebSites.Models.ValidateRequest">
  <TypeSignature Language="C#" Value="public class ValidateRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValidateRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ValidateRequest" />
  <TypeSignature Language="F#" Value="type ValidateRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            リソースの検証要求の内容。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            クロス クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateRequest (string name, string type, string location, string serverFarmId = null, string skuName = null, Nullable&lt;bool&gt; needLinuxWorkers = null, Nullable&lt;bool&gt; isSpot = null, Nullable&lt;int&gt; capacity = null, string hostingEnvironment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string type, string location, string serverFarmId, string skuName, valuetype System.Nullable`1&lt;bool&gt; needLinuxWorkers, valuetype System.Nullable`1&lt;bool&gt; isSpot, valuetype System.Nullable`1&lt;int32&gt; capacity, string hostingEnvironment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As String, location As String, Optional serverFarmId As String = null, Optional skuName As String = null, Optional needLinuxWorkers As Nullable(Of Boolean) = null, Optional isSpot As Nullable(Of Boolean) = null, Optional capacity As Nullable(Of Integer) = null, Optional hostingEnvironment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ValidateRequest : string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.ValidateRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.ValidateRequest (name, type, location, serverFarmId, skuName, needLinuxWorkers, isSpot, capacity, hostingEnvironment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="skuName" Type="System.String" />
        <Parameter Name="needLinuxWorkers" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isSpot" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">リソース名を確認してください。</param>
        <param name="type">リソースの種類の検証に使用します。 使用可能な値が含まれます: 'ServerFarm'、'サイト'</param>
        <param name="location">リソースの予期される場所です。</param>
        <param name="serverFarmId">アプリをホストする App Service プランの ARM リソース ID です。</param>
        <param name="skuName">App Service プランのターゲットの SKU の名前です。</param>
        <param name="needLinuxWorkers">&lt;コード&gt;true&lt;/code&gt; App Service プランが Linux ワーカー以外の場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="isSpot">&lt;コード&gt;true&lt;/code&gt; App Service プランがスポット インスタンス以外の場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="capacity">App Service プラン (VM の数) の容量を対象します。</param>
        <param name="hostingEnvironment">アプリまたは App Service プランを作成する必要が App Service 環境の名前です。</param>
        <summary>
            クロス クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または App Service プラン (VM の数) の容量のターゲットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリまたは App Service プランを作成する必要が App Service 環境の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSpot">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSpot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSpot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.IsSpot" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSpot As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSpot : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.IsSpot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isSpot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; App Service プランがスポット インスタンス以外の場合それ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code&amp; 。gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの予期される場所を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を確認するリソースの名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NeedLinuxWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NeedLinuxWorkers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NeedLinuxWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.NeedLinuxWorkers" />
      <MemberSignature Language="VB.NET" Value="Public Property NeedLinuxWorkers As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NeedLinuxWorkers : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.NeedLinuxWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.needLinuxWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; App Service プランが Linux ワーカー以外の場合それ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code&amp;gt。;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverFarmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーションをホストする App Service プランの ARM リソース ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkuName">
      <MemberSignature Language="C#" Value="public string SkuName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SkuName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.SkuName" />
      <MemberSignature Language="VB.NET" Value="Public Property SkuName As String" />
      <MemberSignature Language="F#" Value="member this.SkuName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.SkuName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.skuName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のターゲットの SKU を App Service プランの名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の検証に使用するリソースの種類。 使用可能な値が含まれます: 'ServerFarm'、'サイト'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ValidateRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="validateRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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