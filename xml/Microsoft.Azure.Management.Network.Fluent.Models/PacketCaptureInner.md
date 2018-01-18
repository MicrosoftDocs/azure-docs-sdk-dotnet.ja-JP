<Type Name="PacketCaptureInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner">
  <TypeSignature Language="C#" Value="public class PacketCaptureInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureInner" />
  <TypeSignature Language="F#" Value="type PacketCaptureInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="ecc75-101">作成するパケットを定義するパラメーターは、操作をキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="ecc75-101">Parameters that define the create packet capture operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ecc75-102">PacketCaptureInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ecc75-102">Initializes a new instance of the PacketCaptureInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureInner (string target, Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation storageLocation, Nullable&lt;int&gt; bytesToCapturePerPacket = null, Nullable&lt;int&gt; totalBytesPerSession = null, Nullable&lt;int&gt; timeLimitInSeconds = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter&gt; filters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string target, class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation storageLocation, valuetype System.Nullable`1&lt;int32&gt; bytesToCapturePerPacket, valuetype System.Nullable`1&lt;int32&gt; totalBytesPerSession, valuetype System.Nullable`1&lt;int32&gt; timeLimitInSeconds, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter&gt; filters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.#ctor(System.String,Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (target As String, storageLocation As PacketCaptureStorageLocation, Optional bytesToCapturePerPacket As Nullable(Of Integer) = null, Optional totalBytesPerSession As Nullable(Of Integer) = null, Optional timeLimitInSeconds As Nullable(Of Integer) = null, Optional filters As IList(Of PacketCaptureFilter) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner : string * Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner (target, storageLocation, bytesToCapturePerPacket, totalBytesPerSession, timeLimitInSeconds, filters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="storageLocation" Type="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation" />
        <Parameter Name="bytesToCapturePerPacket" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalBytesPerSession" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeLimitInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="filters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="ecc75-103">対象のリソースのみの VM の ID は現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="ecc75-103">The ID of the targeted resource, only VM is currently supported.</span></span></param>
        <param name="storageLocation">To be added.</param>
        <param name="bytesToCapturePerPacket"><span data-ttu-id="ecc75-104">数パケットごとに取得 (バイト単位) の残りのバイトが切り捨てられます。</span><span class="sxs-lookup"><span data-stu-id="ecc75-104">Number of bytes captured per packet, the remaining bytes are truncated.</span></span></param>
        <param name="totalBytesPerSession"><span data-ttu-id="ecc75-105">キャプチャ出力の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="ecc75-105">Maximum size of the capture output.</span></span></param>
        <param name="timeLimitInSeconds"><span data-ttu-id="ecc75-106">秒単位でキャプチャ セッションの最大期間です。</span><span class="sxs-lookup"><span data-stu-id="ecc75-106">Maximum duration of the capture session in seconds.</span></span></param>
        <param name="filters">To be added.</param>
        <summary>
            <span data-ttu-id="ecc75-107">PacketCaptureInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ecc75-107">Initializes a new instance of the PacketCaptureInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BytesToCapturePerPacket">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BytesToCapturePerPacket { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BytesToCapturePerPacket" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.BytesToCapturePerPacket" />
      <MemberSignature Language="VB.NET" Value="Public Property BytesToCapturePerPacket As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BytesToCapturePerPacket : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.BytesToCapturePerPacket" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bytesToCapturePerPacket")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecc75-108">パケットごとに取得するバイト数を取得または残りのバイトが切り捨てられます。</span><span class="sxs-lookup"><span data-stu-id="ecc75-108">Gets or sets number of bytes captured per packet, the remaining bytes are truncated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter&gt; Filters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter&gt; Filters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.Filters" />
      <MemberSignature Language="VB.NET" Value="Public Property Filters As IList(Of PacketCaptureFilter)" />
      <MemberSignature Language="F#" Value="member this.Filters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.Filters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation StorageLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation StorageLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.StorageLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageLocation As PacketCaptureStorageLocation" />
      <MemberSignature Language="F#" Value="member this.StorageLocation : Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.StorageLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecc75-109">取得または設定対象のリソースのみの VM の ID は現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="ecc75-109">Gets or sets the ID of the targeted resource, only VM is currently supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeLimitInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeLimitInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeLimitInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.TimeLimitInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeLimitInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeLimitInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.TimeLimitInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeLimitInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecc75-110">取得またはキャプチャ セッションの最大継続時間を秒単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="ecc75-110">Gets or sets maximum duration of the capture session in seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalBytesPerSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalBytesPerSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalBytesPerSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.TotalBytesPerSession" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalBytesPerSession As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalBytesPerSession : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.TotalBytesPerSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalBytesPerSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecc75-111">取得またはキャプチャ出力の最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="ecc75-111">Gets or sets maximum size of the capture output.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="packetCaptureInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ecc75-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ecc75-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ecc75-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ecc75-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>