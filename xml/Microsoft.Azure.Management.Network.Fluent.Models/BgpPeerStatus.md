<Type Name="BgpPeerStatus" FullName="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus">
  <TypeSignature Language="C#" Value="public class BgpPeerStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BgpPeerStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class BgpPeerStatus" />
  <TypeSignature Language="F#" Value="type BgpPeerStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpPeerStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c228c-101">BgpPeerStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c228c-101">Initializes a new instance of the BgpPeerStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpPeerStatus (string localAddress = null, string neighbor = null, Nullable&lt;int&gt; asn = null, string state = null, string connectedDuration = null, Nullable&lt;long&gt; routesReceived = null, Nullable&lt;long&gt; messagesSent = null, Nullable&lt;long&gt; messagesReceived = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string localAddress, string neighbor, valuetype System.Nullable`1&lt;int32&gt; asn, string state, string connectedDuration, valuetype System.Nullable`1&lt;int64&gt; routesReceived, valuetype System.Nullable`1&lt;int64&gt; messagesSent, valuetype System.Nullable`1&lt;int64&gt; messagesReceived) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.#ctor(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional localAddress As String = null, Optional neighbor As String = null, Optional asn As Nullable(Of Integer) = null, Optional state As String = null, Optional connectedDuration As String = null, Optional routesReceived As Nullable(Of Long) = null, Optional messagesSent As Nullable(Of Long) = null, Optional messagesReceived As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus : string * string * Nullable&lt;int&gt; * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus (localAddress, neighbor, asn, state, connectedDuration, routesReceived, messagesSent, messagesReceived)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
        <param name="localAddress">To be added.</param>
        <param name="neighbor">To be added.</param>
        <param name="asn">To be added.</param>
        <param name="state">To be added.</param>
        <param name="connectedDuration">To be added.</param>
        <param name="routesReceived">To be added.</param>
        <param name="messagesSent">To be added.</param>
        <param name="messagesReceived">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Asn">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Asn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Asn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.Asn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Asn As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Asn : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.Asn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c228c-102">リモートの BGP ピアの自律システム番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="c228c-102">Gets the autonomous system number of the remote BGP peer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectedDuration">
      <MemberSignature Language="C#" Value="public string ConnectedDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectedDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.ConnectedDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectedDuration As String" />
      <MemberSignature Language="F#" Value="member this.ConnectedDuration : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.ConnectedDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c228c-103">どのくらいの時間、ピアリングされたの取得します。</span><span class="sxs-lookup"><span data-stu-id="c228c-103">Gets for how long the peering has been up</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalAddress">
      <MemberSignature Language="C#" Value="public string LocalAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.LocalAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalAddress : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.LocalAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c228c-104">仮想ネットワーク ゲートウェイのローカル アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c228c-104">Gets the virtual network gateway's local address</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagesReceived">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessagesReceived { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessagesReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.MessagesReceived" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagesReceived As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessagesReceived : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.MessagesReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c228c-105">受信した BGP メッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c228c-105">Gets the number of BGP messages received</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagesSent">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessagesSent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessagesSent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.MessagesSent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagesSent As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessagesSent : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.MessagesSent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c228c-106">BGP のメッセージ送信の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c228c-106">Gets the number of BGP messages sent</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Neighbor">
      <MemberSignature Language="C#" Value="public string Neighbor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Neighbor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.Neighbor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Neighbor As String" />
      <MemberSignature Language="F#" Value="member this.Neighbor : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.Neighbor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c228c-107">リモートの BGP ピアを取得します。</span><span class="sxs-lookup"><span data-stu-id="c228c-107">Gets the remote BGP peer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RoutesReceived">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RoutesReceived { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RoutesReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.RoutesReceived" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RoutesReceived As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RoutesReceived : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.RoutesReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c228c-108">このピアから学習したルートの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="c228c-108">Gets the number of routes learned from this peer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatus.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c228c-109">BGP ピアの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="c228c-109">Gets the BGP peer state.</span></span> <span data-ttu-id="c228c-110">使用可能な値が含まれます: 'Unknown'、'停止'、'アイドル'、'接続'、'接続'</span><span class="sxs-lookup"><span data-stu-id="c228c-110">Possible values include: 'Unknown', 'Stopped', 'Idle', 'Connecting', 'Connected'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>