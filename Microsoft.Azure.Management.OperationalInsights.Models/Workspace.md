<Type Name="Workspace" FullName="Microsoft.Azure.Management.OperationalInsights.Models.Workspace">
  <TypeSignature Language="C#" Value="public class Workspace : Microsoft.Azure.Management.OperationalInsights.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Workspace extends Microsoft.Azure.Management.OperationalInsights.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
  <TypeSignature Language="VB.NET" Value="Public Class Workspace&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Workspace = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.OperationalInsights.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            最上位のワークスペースのリソースのコンテナーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Workspace ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ワークスペースのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Workspace (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string provisioningState = null, string source = null, string customerId = null, string portalUrl = null, Microsoft.Azure.Management.OperationalInsights.Models.Sku sku = null, Nullable&lt;int&gt; retentionInDays = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string provisioningState, string source, string customerId, string portalUrl, class Microsoft.Azure.Management.OperationalInsights.Models.Sku sku, valuetype System.Nullable`1&lt;int32&gt; retentionInDays, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Sku,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.Workspace : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Sku * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.Workspace (location, id, name, type, tags, provisioningState, source, customerId, portalUrl, sku, retentionInDays, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="customerId" Type="System.String" />
        <Parameter Name="portalUrl" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.OperationalInsights.Models.Sku" />
        <Parameter Name="retentionInDays" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所</param>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="tags">リソース タグ</param>
        <param name="provisioningState">ワークスペースのプロビジョニングの状態。 使用可能な値が含まれます: '作成中'、'成功'、'失敗'、'キャンセル'、'削除'、'ProvisioningAccount'</param>
        <param name="source">ワークスペースのソース。  ソースは、ワークスペースを作成した場所を定義します。 'Azure' は、Azure で作成されたことを意味します。  「外部」は、Operational Insights ポータルを使用して作成されたことを意味します。 この値は、サービス側とクライアント側では読み取り専用に設定されます。</param>
        <param name="customerId">ワークスペースに関連付けられている ID です。 作成時にこの値を設定すると、既存のワークスペースにリンクするために作成されているワークスペースができます。</param>
        <param name="portalUrl">このワークスペースの Operational Insights ポータルの URL です。  この値は、サービス側とクライアント側では読み取り専用に設定されます。</param>
        <param name="sku">ワークスペースの SKU。</param>
        <param name="retentionInDays">日数のワークスペースのデータ保有期間。
            -1 は無制限の Sku の無制限の保有期間を意味します。 730 の日数は、その他のすべての Sku で許可される最大です。 </param>
        <param name="eTag">ワークスペースの ETag です。</param>
        <summary>
            ワークスペースのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomerId">
      <MemberSignature Language="C#" Value="public string CustomerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.CustomerId" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomerId As String" />
      <MemberSignature Language="F#" Value="member this.CustomerId : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.CustomerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワークスペースに関連付けられている ID を設定します。  作成時にこの値を設定すると、既存のワークスペースにリンクするために作成されているワークスペースができます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワークスペースの ETag を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PortalUrl">
      <MemberSignature Language="C#" Value="public string PortalUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PortalUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.PortalUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property PortalUrl As String" />
      <MemberSignature Language="F#" Value="member this.PortalUrl : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.PortalUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.portalUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのワークスペースの Operational Insights ポータルの URL を設定します。  この値は、サービス側とクライアント側では読み取り専用に設定されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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
            取得またはワークスペースのプロビジョニングの状態を設定します。 使用可能な値が含まれます: '作成中'、'成功'、'失敗'、'キャンセル'、'削除'、'ProvisioningAccount'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.RetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionInDays As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetentionInDays : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.RetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワークスペースのデータ保有期間を日に設定します。 -1 は無制限の Sku の無制限の保有期間を意味します。 730 の日数は、その他のすべての Sku で許可される最大です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.OperationalInsights.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.OperationalInsights.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.OperationalInsights.Models.Sku with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Sku" />
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
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワークスペースの SKU を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはワークスペースのソースを設定します。  ソースは、ワークスペースを作成した場所を定義します。 'Azure' は、Azure で作成されたことを意味します。 「外部」は、Operational Insights ポータルを使用して作成されたことを意味します。 この値は、サービス側とクライアント側では読み取り専用に設定されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.Workspace.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="workspace.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
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