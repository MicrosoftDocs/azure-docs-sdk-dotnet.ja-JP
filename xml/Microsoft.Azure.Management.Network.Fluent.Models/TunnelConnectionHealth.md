<Type Name="TunnelConnectionHealth" FullName="Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth">
  <TypeSignature Language="C#" Value="public class TunnelConnectionHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TunnelConnectionHealth extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth" />
  <TypeSignature Language="VB.NET" Value="Public Class TunnelConnectionHealth" />
  <TypeSignature Language="F#" Value="type TunnelConnectionHealth = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dea9a-101">VirtualNetworkGatewayConnection プロパティ</span><span class="sxs-lookup"><span data-stu-id="dea9a-101">VirtualNetworkGatewayConnection properties</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TunnelConnectionHealth ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dea9a-102">TunnelConnectionHealth クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dea9a-102">Initializes a new instance of the TunnelConnectionHealth class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TunnelConnectionHealth (string tunnel = null, string connectionStatus = null, Nullable&lt;long&gt; ingressBytesTransferred = null, Nullable&lt;long&gt; egressBytesTransferred = null, string lastConnectionEstablishedUtcTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tunnel, string connectionStatus, valuetype System.Nullable`1&lt;int64&gt; ingressBytesTransferred, valuetype System.Nullable`1&lt;int64&gt; egressBytesTransferred, string lastConnectionEstablishedUtcTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.#ctor(System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tunnel As String = null, Optional connectionStatus As String = null, Optional ingressBytesTransferred As Nullable(Of Long) = null, Optional egressBytesTransferred As Nullable(Of Long) = null, Optional lastConnectionEstablishedUtcTime As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth : string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth (tunnel, connectionStatus, ingressBytesTransferred, egressBytesTransferred, lastConnectionEstablishedUtcTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tunnel" Type="System.String" />
        <Parameter Name="connectionStatus" Type="System.String" />
        <Parameter Name="ingressBytesTransferred" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="egressBytesTransferred" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="lastConnectionEstablishedUtcTime" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tunnel"><span data-ttu-id="dea9a-103">トンネルの名前です。</span><span class="sxs-lookup"><span data-stu-id="dea9a-103">Tunnel name.</span></span></param>
        <param name="connectionStatus"><span data-ttu-id="dea9a-104">仮想ネットワーク ゲートウェイ接続の状態。</span><span class="sxs-lookup"><span data-stu-id="dea9a-104">Virtual network Gateway connection status.</span></span> <span data-ttu-id="dea9a-105">使用可能な値が含まれます: 'Unknown'、'接続'、'接続'、'NotConnected'</span><span class="sxs-lookup"><span data-stu-id="dea9a-105">Possible values include: 'Unknown', 'Connecting', 'Connected', 'NotConnected'</span></span></param>
        <param name="ingressBytesTransferred"><span data-ttu-id="dea9a-106">この接続で転送された受信バイト数</span><span class="sxs-lookup"><span data-stu-id="dea9a-106">The Ingress Bytes Transferred in this connection</span></span></param>
        <param name="egressBytesTransferred"><span data-ttu-id="dea9a-107">この接続で転送された送信バイト数</span><span class="sxs-lookup"><span data-stu-id="dea9a-107">The Egress Bytes Transferred in this connection</span></span></param>
        <param name="lastConnectionEstablishedUtcTime"><span data-ttu-id="dea9a-108">Utc 形式で接続が確立された時刻。</span><span class="sxs-lookup"><span data-stu-id="dea9a-108">The time at which connection was established in Utc format.</span></span></param>
        <summary>
            <span data-ttu-id="dea9a-109">TunnelConnectionHealth クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dea9a-109">Initializes a new instance of the TunnelConnectionHealth class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStatus">
      <MemberSignature Language="C#" Value="public string ConnectionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.ConnectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionStatus As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionStatus : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.ConnectionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea9a-110">仮想ネットワーク ゲートウェイ接続の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="dea9a-110">Gets virtual network Gateway connection status.</span></span> <span data-ttu-id="dea9a-111">使用可能な値が含まれます: 'Unknown'、'接続'、'接続'、'NotConnected'</span><span class="sxs-lookup"><span data-stu-id="dea9a-111">Possible values include: 'Unknown', 'Connecting', 'Connected', 'NotConnected'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EgressBytesTransferred">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; EgressBytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; EgressBytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.EgressBytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EgressBytesTransferred As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.EgressBytesTransferred : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.EgressBytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="egressBytesTransferred")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea9a-112">この接続で転送送信バイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="dea9a-112">Gets the Egress Bytes Transferred in this connection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IngressBytesTransferred">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IngressBytesTransferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IngressBytesTransferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.IngressBytesTransferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IngressBytesTransferred As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IngressBytesTransferred : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.IngressBytesTransferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ingressBytesTransferred")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea9a-113">この接続で転送受信バイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="dea9a-113">Gets the Ingress Bytes Transferred in this connection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastConnectionEstablishedUtcTime">
      <MemberSignature Language="C#" Value="public string LastConnectionEstablishedUtcTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastConnectionEstablishedUtcTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.LastConnectionEstablishedUtcTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastConnectionEstablishedUtcTime As String" />
      <MemberSignature Language="F#" Value="member this.LastConnectionEstablishedUtcTime : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.LastConnectionEstablishedUtcTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastConnectionEstablishedUtcTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea9a-114">Utc 形式で接続が確立された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="dea9a-114">Gets the time at which connection was established in Utc format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tunnel">
      <MemberSignature Language="C#" Value="public string Tunnel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tunnel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.Tunnel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tunnel As String" />
      <MemberSignature Language="F#" Value="member this.Tunnel : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.TunnelConnectionHealth.Tunnel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tunnel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dea9a-115">トンネルの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="dea9a-115">Gets tunnel name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>