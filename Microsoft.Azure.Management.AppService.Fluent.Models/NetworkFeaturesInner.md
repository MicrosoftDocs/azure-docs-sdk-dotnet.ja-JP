<Type Name="NetworkFeaturesInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner">
  <TypeSignature Language="C#" Value="public class NetworkFeaturesInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkFeaturesInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkFeaturesInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type NetworkFeaturesInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="466b1-101">(現在の VNET 統合とハイブリッド接続) アプリ用のネットワーク機能の完全なビューです。</span><span class="sxs-lookup"><span data-stu-id="466b1-101">Full view of network features for an app (presently VNET integration and Hybrid Connections).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkFeaturesInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="466b1-102">NetworkFeaturesInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="466b1-102">Initializes a new instance of the NetworkFeaturesInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkFeaturesInner (string id = null, string name = null, string kind = null, string type = null, string virtualNetworkName = null, Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner virtualNetworkConnection = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner&gt; hybridConnections = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; hybridConnectionsV2 = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string virtualNetworkName, class Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner virtualNetworkConnection, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner&gt; hybridConnections, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; hybridConnectionsV2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.#ctor(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional virtualNetworkName As String = null, Optional virtualNetworkConnection As VnetInfoInner = null, Optional hybridConnections As IList(Of RelayServiceConnectionEntityInner) = null, Optional hybridConnectionsV2 As IList(Of HybridConnectionInner) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner : string * string * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner (id, name, kind, type, virtualNetworkName, virtualNetworkConnection, hybridConnections, hybridConnectionsV2)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkConnection" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner" />
        <Parameter Name="hybridConnections" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner&gt;" />
        <Parameter Name="hybridConnectionsV2" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="virtualNetworkName">To be added.</param>
        <param name="virtualNetworkConnection">To be added.</param>
        <param name="hybridConnections">To be added.</param>
        <param name="hybridConnectionsV2">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HybridConnections">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner&gt; HybridConnections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner&gt; HybridConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.HybridConnections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HybridConnections As IList(Of RelayServiceConnectionEntityInner)" />
      <MemberSignature Language="F#" Value="member this.HybridConnections : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.HybridConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hybridConnections")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RelayServiceConnectionEntityInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="466b1-103">ハイブリッド接続の概要ビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="466b1-103">Gets the Hybrid Connections summary view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HybridConnectionsV2">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; HybridConnectionsV2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt; HybridConnectionsV2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.HybridConnectionsV2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HybridConnectionsV2 As IList(Of HybridConnectionInner)" />
      <MemberSignature Language="F#" Value="member this.HybridConnectionsV2 : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.HybridConnectionsV2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hybridConnectionsV2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HybridConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="466b1-104">ハイブリッド接続 V2 を取得します (Service Bus) を表示します。</span><span class="sxs-lookup"><span data-stu-id="466b1-104">Gets the Hybrid Connection V2 (Service Bus) view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkConnection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner VirtualNetworkConnection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner VirtualNetworkConnection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.VirtualNetworkConnection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkConnection As VnetInfoInner" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkConnection : Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.VirtualNetworkConnection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkConnection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.VnetInfoInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="466b1-105">仮想ネットワークの概要ビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="466b1-105">Gets the Virtual Network summary view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkName">
      <MemberSignature Language="C#" Value="public string VirtualNetworkName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualNetworkName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.VirtualNetworkName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkName As String" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.NetworkFeaturesInner.VirtualNetworkName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="466b1-106">仮想ネットワーク名を取得します。</span><span class="sxs-lookup"><span data-stu-id="466b1-106">Gets the Virtual Network name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>