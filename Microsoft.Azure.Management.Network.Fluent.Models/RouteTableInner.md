<Type Name="RouteTableInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner">
  <TypeSignature Language="C#" Value="public class RouteTableInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RouteTableInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner" />
  <TypeSignature Language="VB.NET" Value="Public Class RouteTableInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type RouteTableInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            テーブル リソースをルーティングします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteTableInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RouteTableInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RouteTableInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; routes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; subnets = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; routes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; subnets, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.RouteInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional routes As IList(Of RouteInner) = null, Optional subnets As IList(Of SubnetInner) = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner (location, id, name, type, tags, routes, subnets, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="routes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;" />
        <Parameter Name="subnets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="routes">ルート テーブル内に含まれるルートのコレクション。</param>
        <param name="subnets">サブネットへの参照のコレクション。</param>
        <param name="provisioningState">リソースのプロビジョニングの状態。 使用可能な値が: '更新'、'削除' および '失敗' です。</param>
        <param name="etag">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</param>
        <summary>
            RouteTableInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得またはリソースのプロビジョニングの状態を設定します。 使用可能な値が: '更新'、'削除' および '失敗' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Routes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; Routes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; Routes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.Routes" />
      <MemberSignature Language="VB.NET" Value="Public Property Routes As IList(Of RouteInner)" />
      <MemberSignature Language="F#" Value="member this.Routes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.Routes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、ルート テーブル内に含まれるルートのコレクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; Subnets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subnets As IList(Of SubnetInner)" />
      <MemberSignature Language="F#" Value="member this.Subnets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サブネットへの参照のコレクションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>