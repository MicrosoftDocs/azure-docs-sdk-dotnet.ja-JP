<Type Name="PacketCaptureParameters" FullName="Microsoft.Azure.Management.Network.Models.PacketCaptureParameters">
  <TypeSignature Language="C#" Value="public class PacketCaptureParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureParameters" />
  <TypeSignature Language="F#" Value="type PacketCaptureParameters = class" />
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
            <span data-ttu-id="94027-101">作成するパケットを定義するパラメーターは、操作をキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="94027-101">Parameters that define the create packet capture operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.#ctor" />
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
            <span data-ttu-id="94027-102">PacketCaptureParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="94027-102">Initializes a new instance of the PacketCaptureParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureParameters (string target, Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation storageLocation, Nullable&lt;int&gt; bytesToCapturePerPacket = null, Nullable&lt;int&gt; totalBytesPerSession = null, Nullable&lt;int&gt; timeLimitInSeconds = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; filters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string target, class Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation storageLocation, valuetype System.Nullable`1&lt;int32&gt; bytesToCapturePerPacket, valuetype System.Nullable`1&lt;int32&gt; totalBytesPerSession, valuetype System.Nullable`1&lt;int32&gt; timeLimitInSeconds, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; filters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.#ctor(System.String,Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.PacketCaptureFilter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (target As String, storageLocation As PacketCaptureStorageLocation, Optional bytesToCapturePerPacket As Nullable(Of Integer) = null, Optional totalBytesPerSession As Nullable(Of Integer) = null, Optional timeLimitInSeconds As Nullable(Of Integer) = null, Optional filters As IList(Of PacketCaptureFilter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.PacketCaptureParameters : string * Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; -&gt; Microsoft.Azure.Management.Network.Models.PacketCaptureParameters" Usage="new Microsoft.Azure.Management.Network.Models.PacketCaptureParameters (target, storageLocation, bytesToCapturePerPacket, totalBytesPerSession, timeLimitInSeconds, filters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="storageLocation" Type="Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation" />
        <Parameter Name="bytesToCapturePerPacket" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalBytesPerSession" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeLimitInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="filters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="94027-103">対象のリソースのみの VM の ID は現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="94027-103">The ID of the targeted resource, only VM is currently supported.</span></span></param>
        <param name="storageLocation">To be added.</param>
        <param name="bytesToCapturePerPacket"><span data-ttu-id="94027-104">数パケットごとに取得 (バイト単位) の残りのバイトが切り捨てられます。</span><span class="sxs-lookup"><span data-stu-id="94027-104">Number of bytes captured per packet, the remaining bytes are truncated.</span></span></param>
        <param name="totalBytesPerSession"><span data-ttu-id="94027-105">キャプチャ出力の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="94027-105">Maximum size of the capture output.</span></span></param>
        <param name="timeLimitInSeconds"><span data-ttu-id="94027-106">秒単位でキャプチャ セッションの最大期間です。</span><span class="sxs-lookup"><span data-stu-id="94027-106">Maximum duration of the capture session in seconds.</span></span></param>
        <param name="filters">To be added.</param>
        <summary>
            <span data-ttu-id="94027-107">PacketCaptureParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="94027-107">Initializes a new instance of the PacketCaptureParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BytesToCapturePerPacket">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BytesToCapturePerPacket { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BytesToCapturePerPacket" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.BytesToCapturePerPacket" />
      <MemberSignature Language="VB.NET" Value="Public Property BytesToCapturePerPacket As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BytesToCapturePerPacket : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.BytesToCapturePerPacket" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bytesToCapturePerPacket")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94027-108">パケットごとに取得するバイト数を取得または残りのバイトが切り捨てられます。</span><span class="sxs-lookup"><span data-stu-id="94027-108">Gets or sets number of bytes captured per packet, the remaining bytes are truncated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; Filters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; Filters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.Filters" />
      <MemberSignature Language="VB.NET" Value="Public Property Filters As IList(Of PacketCaptureFilter)" />
      <MemberSignature Language="F#" Value="member this.Filters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.Filters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation StorageLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation StorageLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.StorageLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageLocation As PacketCaptureStorageLocation" />
      <MemberSignature Language="F#" Value="member this.StorageLocation : Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.StorageLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94027-109">取得または設定対象のリソースのみの VM の ID は現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="94027-109">Gets or sets the ID of the targeted resource, only VM is currently supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeLimitInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeLimitInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeLimitInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.TimeLimitInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeLimitInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeLimitInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.TimeLimitInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeLimitInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94027-110">取得またはキャプチャ セッションの最大継続時間を秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="94027-110">Gets or sets maximum duration of the capture session in seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalBytesPerSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalBytesPerSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalBytesPerSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.TotalBytesPerSession" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalBytesPerSession As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalBytesPerSession : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.TotalBytesPerSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalBytesPerSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94027-111">取得またはキャプチャ出力の最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="94027-111">Gets or sets maximum size of the capture output.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="packetCaptureParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94027-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="94027-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="94027-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="94027-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>