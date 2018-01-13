<Type Name="PacketCaptureQueryStatusResult" FullName="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult">
  <TypeSignature Language="C#" Value="public class PacketCaptureQueryStatusResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureQueryStatusResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureQueryStatusResult" />
  <TypeSignature Language="F#" Value="type PacketCaptureQueryStatusResult = class" />
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
            パケット キャプチャ セッションの状態です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureQueryStatusResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.#ctor" />
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
            PacketCaptureQueryStatusResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureQueryStatusResult (string name = null, string id = null, Nullable&lt;DateTime&gt; captureStartTime = null, string packetCaptureStatus = null, string stopReason = null, System.Collections.Generic.IList&lt;string&gt; packetCaptureError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; captureStartTime, string packetCaptureStatus, string stopReason, class System.Collections.Generic.IList`1&lt;string&gt; packetCaptureError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional captureStartTime As Nullable(Of DateTime) = null, Optional packetCaptureStatus As String = null, Optional stopReason As String = null, Optional packetCaptureError As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult : string * string * Nullable&lt;DateTime&gt; * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult" Usage="new Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult (name, id, captureStartTime, packetCaptureStatus, stopReason, packetCaptureError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="captureStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="packetCaptureStatus" Type="System.String" />
        <Parameter Name="stopReason" Type="System.String" />
        <Parameter Name="packetCaptureError" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">パケット キャプチャ リソースの名前。</param>
        <param name="id">パケット キャプチャ リソースの ID。</param>
        <param name="captureStartTime">パケット キャプチャ セッションの開始時刻です。</param>
        <param name="packetCaptureStatus">パケット キャプチャ セッションの状態。 使用可能な値が含まれます: 'NotStarted'、'Running'、'停止'、'Error'、'Unknown'</param>
        <param name="stopReason">理由を現在のパケット キャプチャ セッションが停止されました。</param>
        <param name="packetCaptureError">パケット キャプチャ セッションのエラーの一覧。</param>
        <summary>
            PacketCaptureQueryStatusResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaptureStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CaptureStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CaptureStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.CaptureStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CaptureStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CaptureStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.CaptureStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="captureStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパケット キャプチャ セッションの開始時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパケット キャプチャ リソースの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            取得またはパケット キャプチャ リソースの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PacketCaptureError">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PacketCaptureError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PacketCaptureError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.PacketCaptureError" />
      <MemberSignature Language="VB.NET" Value="Public Property PacketCaptureError As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PacketCaptureError : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.PacketCaptureError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="packetCaptureError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパケット キャプチャ セッションのエラーの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PacketCaptureStatus">
      <MemberSignature Language="C#" Value="public string PacketCaptureStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PacketCaptureStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.PacketCaptureStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property PacketCaptureStatus As String" />
      <MemberSignature Language="F#" Value="member this.PacketCaptureStatus : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.PacketCaptureStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="packetCaptureStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパケット キャプチャ セッションの状態を設定します。 使用可能な値が含まれます: 'NotStarted'、'Running'、'停止'、'Error'、'Unknown'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopReason">
      <MemberSignature Language="C#" Value="public string StopReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StopReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.StopReason" />
      <MemberSignature Language="VB.NET" Value="Public Property StopReason As String" />
      <MemberSignature Language="F#" Value="member this.StopReason : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureQueryStatusResult.StopReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のため、現在のパケット キャプチャ セッションが停止されました。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>