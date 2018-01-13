<Type Name="NodeTypeDescription" FullName="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription">
  <TypeSignature Language="C#" Value="public class NodeTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeTypeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeTypeDescription" />
  <TypeSignature Language="F#" Value="type NodeTypeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ノードの型を記述、クラスターでは、各ノードの種類は、クラスター内のノードのサブツール セットを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeTypeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NodeTypeDescription クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeTypeDescription (string name, int clientConnectionEndpointPort, int httpGatewayEndpointPort, bool isPrimary, int vmInstanceCount, System.Collections.Generic.IDictionary&lt;string,string&gt; placementProperties = null, System.Collections.Generic.IDictionary&lt;string,string&gt; capacities = null, string durabilityLevel = null, Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription applicationPorts = null, Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription ephemeralPorts = null, Nullable&lt;int&gt; reverseProxyEndpointPort = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int32 clientConnectionEndpointPort, int32 httpGatewayEndpointPort, bool isPrimary, int32 vmInstanceCount, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; placementProperties, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; capacities, string durabilityLevel, class Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription applicationPorts, class Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription ephemeralPorts, valuetype System.Nullable`1&lt;int32&gt; reverseProxyEndpointPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.#ctor(System.String,System.Int32,System.Int32,System.Boolean,System.Int32,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription,Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, clientConnectionEndpointPort As Integer, httpGatewayEndpointPort As Integer, isPrimary As Boolean, vmInstanceCount As Integer, Optional placementProperties As IDictionary(Of String, String) = null, Optional capacities As IDictionary(Of String, String) = null, Optional durabilityLevel As String = null, Optional applicationPorts As EndpointRangeDescription = null, Optional ephemeralPorts As EndpointRangeDescription = null, Optional reverseProxyEndpointPort As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription : string * int * int * bool * int * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription * Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription (name, clientConnectionEndpointPort, httpGatewayEndpointPort, isPrimary, vmInstanceCount, placementProperties, capacities, durabilityLevel, applicationPorts, ephemeralPorts, reverseProxyEndpointPort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="clientConnectionEndpointPort" Type="System.Int32" />
        <Parameter Name="httpGatewayEndpointPort" Type="System.Int32" />
        <Parameter Name="isPrimary" Type="System.Boolean" />
        <Parameter Name="vmInstanceCount" Type="System.Int32" />
        <Parameter Name="placementProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="capacities" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="durabilityLevel" Type="System.String" />
        <Parameter Name="applicationPorts" Type="Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription" />
        <Parameter Name="ephemeralPorts" Type="Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription" />
        <Parameter Name="reverseProxyEndpointPort" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name">ノードの種類の名前</param>
        <param name="clientConnectionEndpointPort">TCP クラスター管理用エンドポイント ポート</param>
        <param name="httpGatewayEndpointPort">HTTP クラスター管理用エンドポイント ポート</param>
        <param name="isPrimary">これを主ノード型としてマークします。</param>
        <param name="vmInstanceCount">ノードの種類のノード インスタンスの数</param>
        <param name="placementProperties">特定のサービス (ワークロード) を実行する場所を示すために使用できるノードの種類のノードに適用される配置タグ</param>
        <param name="capacities">ノードの種類のノードに適用される容量タグ、クラスター リソース マネージャーを使用してこれらのタグがノード a のリソースの量を理解するには</param>
        <param name="durabilityLevel">Nodetype の持続性のレベルです。 使用可能な値が含まれます: 'ブロンズ'、'銀色'、'Gold'</param>
        <param name="applicationPorts">アプリケーションで使用されるポート</param>
        <param name="ephemeralPorts">システムによって割り当てアプリケーション ポート</param>
        <param name="reverseProxyEndpointPort">リバース プロキシによって使用されるエンドポイント</param>
        <summary>
            NodeTypeDescription クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPorts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription ApplicationPorts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription ApplicationPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ApplicationPorts" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPorts As EndpointRangeDescription" />
      <MemberSignature Language="F#" Value="member this.ApplicationPorts : Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ApplicationPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPorts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーションで使用されるポートの設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Capacities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Capacities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Capacities" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacities As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Capacities : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Capacities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定容量タグ ノードに適用、ノードの種類のクラスター リソース マネージャーで使用してこれらのタグがノード a のリソースの量を理解するには
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnectionEndpointPort">
      <MemberSignature Language="C#" Value="public int ClientConnectionEndpointPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ClientConnectionEndpointPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ClientConnectionEndpointPort" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientConnectionEndpointPort As Integer" />
      <MemberSignature Language="F#" Value="member this.ClientConnectionEndpointPort : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ClientConnectionEndpointPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientConnectionEndpointPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または TCP のクラスター管理用エンドポイント ポートを設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DurabilityLevel">
      <MemberSignature Language="C#" Value="public string DurabilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DurabilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.DurabilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property DurabilityLevel As String" />
      <MemberSignature Language="F#" Value="member this.DurabilityLevel : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.DurabilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="durabilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または nodetype の持続性のレベルを設定します。 使用可能な値が含まれます: 'ブロンズ'、'銀色'、'Gold'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EphemeralPorts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription EphemeralPorts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription EphemeralPorts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.EphemeralPorts" />
      <MemberSignature Language="VB.NET" Value="Public Property EphemeralPorts As EndpointRangeDescription" />
      <MemberSignature Language="F#" Value="member this.EphemeralPorts : Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.EphemeralPorts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ephemeralPorts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.EndpointRangeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはシステムによって割り当てアプリケーション ポートの設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpGatewayEndpointPort">
      <MemberSignature Language="C#" Value="public int HttpGatewayEndpointPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpGatewayEndpointPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.HttpGatewayEndpointPort" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpGatewayEndpointPort As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpGatewayEndpointPort : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.HttpGatewayEndpointPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="httpGatewayEndpointPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスター管理用エンドポイント ポートを HTTP に設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrimary">
      <MemberSignature Language="C#" Value="public bool IsPrimary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPrimary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.IsPrimary" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPrimary As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPrimary : bool with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.IsPrimary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isPrimary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定はこの主ノード型としてマークします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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
            取得または設定 ノードの種類の名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; PlacementProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; PlacementProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.PlacementProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementProperties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.PlacementProperties : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.PlacementProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="placementProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の特定のサービス (ワークロード) を実行する場所を示すために使用できるノードの種類のノードに適用される配置タグ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReverseProxyEndpointPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ReverseProxyEndpointPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ReverseProxyEndpointPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ReverseProxyEndpointPort" />
      <MemberSignature Language="VB.NET" Value="Public Property ReverseProxyEndpointPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ReverseProxyEndpointPort : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.ReverseProxyEndpointPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reverseProxyEndpointPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリバース プロキシによって使用されるエンドポイントの設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeTypeDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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
    <Member MemberName="VmInstanceCount">
      <MemberSignature Language="C#" Value="public int VmInstanceCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 VmInstanceCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.VmInstanceCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VmInstanceCount As Integer" />
      <MemberSignature Language="F#" Value="member this.VmInstanceCount : int with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription.VmInstanceCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmInstanceCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはノードの種類のノード インスタンスの数を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>