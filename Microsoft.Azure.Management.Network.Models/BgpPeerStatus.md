<Type Name="BgpPeerStatus" FullName="Microsoft.Azure.Management.Network.Models.BgpPeerStatus">
  <TypeSignature Language="C#" Value="public class BgpPeerStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BgpPeerStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.BgpPeerStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class BgpPeerStatus" />
  <TypeSignature Language="F#" Value="type BgpPeerStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7289b-101">BGP ピアのステータスの詳細</span><span class="sxs-lookup"><span data-stu-id="7289b-101">BGP peer status details</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpPeerStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7289b-102">BgpPeerStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7289b-102">Initializes a new instance of the BgpPeerStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpPeerStatus (string localAddress = null, string neighbor = null, Nullable&lt;int&gt; asn = null, string state = null, string connectedDuration = null, Nullable&lt;long&gt; routesReceived = null, Nullable&lt;long&gt; messagesSent = null, Nullable&lt;long&gt; messagesReceived = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string localAddress, string neighbor, valuetype System.Nullable`1&lt;int32&gt; asn, string state, string connectedDuration, valuetype System.Nullable`1&lt;int64&gt; routesReceived, valuetype System.Nullable`1&lt;int64&gt; messagesSent, valuetype System.Nullable`1&lt;int64&gt; messagesReceived) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.#ctor(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional localAddress As String = null, Optional neighbor As String = null, Optional asn As Nullable(Of Integer) = null, Optional state As String = null, Optional connectedDuration As String = null, Optional routesReceived As Nullable(Of Long) = null, Optional messagesSent As Nullable(Of Long) = null, Optional messagesReceived As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.BgpPeerStatus : string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.Network.Models.BgpPeerStatus" Usage="new Microsoft.Azure.Management.Network.Models.BgpPeerStatus (localAddress, neighbor, asn, state, connectedDuration, routesReceived, messagesSent, messagesReceived)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="localAddress" Type="System.String" />
        <Parameter Name="neighbor" Type="System.String" />
        <Parameter Name="asn" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="connectedDuration" Type="System.String" />
        <Parameter Name="routesReceived" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="messagesSent" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="messagesReceived" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="localAddress"><span data-ttu-id="7289b-103">仮想ネットワーク ゲートウェイのローカル アドレス</span><span class="sxs-lookup"><span data-stu-id="7289b-103">The virtual network gateway's local address</span></span></param>
        <param name="neighbor"><span data-ttu-id="7289b-104">リモートの BGP ピア</span><span class="sxs-lookup"><span data-stu-id="7289b-104">The remote BGP peer</span></span></param>
        <param name="asn"><span data-ttu-id="7289b-105">リモートの BGP ピアの自律システム番号</span><span class="sxs-lookup"><span data-stu-id="7289b-105">The autonomous system number of the remote BGP peer</span></span></param>
        <param name="state"><span data-ttu-id="7289b-106">BGP ピアの状態。</span><span class="sxs-lookup"><span data-stu-id="7289b-106">The BGP peer state.</span></span> <span data-ttu-id="7289b-107">使用可能な値が含まれます: 'Unknown'、'停止'、'アイドル'、'接続'、'接続'</span><span class="sxs-lookup"><span data-stu-id="7289b-107">Possible values include: 'Unknown', 'Stopped', 'Idle', 'Connecting', 'Connected'</span></span></param>
        <param name="connectedDuration"><span data-ttu-id="7289b-108">どのくらいの期間のピアリングされてが稼動してください。</span><span class="sxs-lookup"><span data-stu-id="7289b-108">For how long the peering has been up</span></span></param>
        <param name="routesReceived"><span data-ttu-id="7289b-109">このピアから学習したルートの数</span><span class="sxs-lookup"><span data-stu-id="7289b-109">The number of routes learned from this peer</span></span></param>
        <param name="messagesSent"><span data-ttu-id="7289b-110">BGP のメッセージ送信の数</span><span class="sxs-lookup"><span data-stu-id="7289b-110">The number of BGP messages sent</span></span></param>
        <param name="messagesReceived"><span data-ttu-id="7289b-111">受信 BGP メッセージの数</span><span class="sxs-lookup"><span data-stu-id="7289b-111">The number of BGP messages received</span></span></param>
        <summary>
            <span data-ttu-id="7289b-112">BgpPeerStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7289b-112">Initializes a new instance of the BgpPeerStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Asn">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Asn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Asn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.Asn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Asn As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Asn : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatus.Asn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="asn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7289b-113">リモートの BGP ピアの自律システム番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="7289b-113">Gets the autonomous system number of the remote BGP peer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectedDuration">
      <MemberSignature Language="C#" Value="public string ConnectedDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectedDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.ConnectedDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectedDuration As String" />
      <MemberSignature Language="F#" Value="member this.ConnectedDuration : string" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatus.ConnectedDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectedDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7289b-114">どのくらいの時間、ピアリングされたの取得します。</span><span class="sxs-lookup"><span data-stu-id="7289b-114">Gets for how long the peering has been up</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalAddress">
      <MemberSignature Language="C#" Value="public string LocalAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.LocalAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalAddress : string" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatus.LocalAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7289b-115">仮想ネットワーク ゲートウェイのローカル アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="7289b-115">Gets the virtual network gateway's local address</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagesReceived">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessagesReceived { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessagesReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.MessagesReceived" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagesReceived As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessagesReceived : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatus.MessagesReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="messagesReceived")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7289b-116">受信した BGP メッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="7289b-116">Gets the number of BGP messages received</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagesSent">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessagesSent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessagesSent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.MessagesSent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagesSent As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessagesSent : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatus.MessagesSent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="messagesSent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7289b-117">BGP のメッセージ送信の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="7289b-117">Gets the number of BGP messages sent</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Neighbor">
      <MemberSignature Language="C#" Value="public string Neighbor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Neighbor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.Neighbor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Neighbor As String" />
      <MemberSignature Language="F#" Value="member this.Neighbor : string" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatus.Neighbor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="neighbor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7289b-118">リモートの BGP ピアを取得します。</span><span class="sxs-lookup"><span data-stu-id="7289b-118">Gets the remote BGP peer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoutesReceived">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RoutesReceived { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RoutesReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.RoutesReceived" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RoutesReceived As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RoutesReceived : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatus.RoutesReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="routesReceived")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7289b-119">このピアから学習したルートの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="7289b-119">Gets the number of routes learned from this peer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpPeerStatus.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Network.Models.BgpPeerStatus.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7289b-120">BGP ピアの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="7289b-120">Gets the BGP peer state.</span></span> <span data-ttu-id="7289b-121">使用可能な値が含まれます: 'Unknown'、'停止'、'アイドル'、'接続'、'接続'</span><span class="sxs-lookup"><span data-stu-id="7289b-121">Possible values include: 'Unknown', 'Stopped', 'Idle', 'Connecting', 'Connected'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>