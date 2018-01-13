<Type Name="ManagementGroup" FullName="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup">
  <TypeSignature Language="C#" Value="public class ManagementGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementGroup" />
  <TypeSignature Language="F#" Value="type ManagementGroup = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            ワークスペースに接続されている管理グループ
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ManagementGroup クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroup (Nullable&lt;int&gt; serverCount = null, Nullable&lt;bool&gt; isGateway = null, string name = null, string id = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; dataReceived = null, string version = null, string sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; serverCount, valuetype System.Nullable`1&lt;bool&gt; isGateway, string name, string id, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; dataReceived, string version, string sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.#ctor(System.Nullable{System.Int32},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serverCount As Nullable(Of Integer) = null, Optional isGateway As Nullable(Of Boolean) = null, Optional name As String = null, Optional id As String = null, Optional created As Nullable(Of DateTime) = null, Optional dataReceived As Nullable(Of DateTime) = null, Optional version As String = null, Optional sku As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup : Nullable&lt;int&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup (serverCount, isGateway, name, id, created, dataReceived, version, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serverCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isGateway" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="dataReceived" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="sku" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serverCount">サーバーの数は、管理グループに接続します。</param>
        <param name="isGateway">取得または管理グループがゲートウェイであるかどうかを示す値を設定します。</param>
        <param name="name">管理グループの名前。</param>
        <param name="id">管理グループの一意の ID。</param>
        <param name="created">管理グループが作成された日時。</param>
        <param name="dataReceived">管理グループがデータを受信しました最終日時。</param>
        <param name="version">管理グループが管理している System Center のバージョン。</param>
        <param name="sku">SKU の System Center 管理グループが管理しています。</param>
        <summary>
            ManagementGroup クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Created { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Created" />
      <MemberSignature Language="VB.NET" Value="Public Property Created As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Created : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.created")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理グループが作成された日付と時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataReceived">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DataReceived { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DataReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.DataReceived" />
      <MemberSignature Language="VB.NET" Value="Public Property DataReceived As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DataReceived : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.DataReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataReceived")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理グループがデータを受信する最後の datetime を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理グループの一意の ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsGateway">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsGateway { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsGateway" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.IsGateway" />
      <MemberSignature Language="VB.NET" Value="Public Property IsGateway As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsGateway : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.IsGateway" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isGateway")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理グループがゲートウェイであるかどうかを示す値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            取得または管理グループの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ServerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ServerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.ServerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ServerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.ServerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理グループに接続されているサーバーの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public string Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As String" />
      <MemberSignature Language="F#" Value="member this.Sku : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、SKU の System Center 管理グループが管理しています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理グループが管理している System Center のバージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>