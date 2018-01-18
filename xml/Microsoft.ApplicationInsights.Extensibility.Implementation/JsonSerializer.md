<Type Name="JsonSerializer" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer">
  <TypeSignature Language="C#" Value="public static class JsonSerializer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JsonSerializer extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonSerializer" />
  <TypeSignature Language="F#" Value="type JsonSerializer = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="23e15-101">シリアル化し、JSON 文字列にテレメトリ項目を圧縮します。</span><span class="sxs-lookup"><span data-stu-id="23e15-101">Serializes and compress the telemetry items into a JSON string.</span></span> <span data-ttu-id="23e15-102">圧縮は行われます GZIP を使用してその API はサポートされているために、Windows Phone 8 の圧縮は無効になります。</span><span class="sxs-lookup"><span data-stu-id="23e15-102">Compression will be done using GZIP, for Windows Phone 8 compression will be disabled because there is API support for it.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CompressionType">
      <MemberSignature Language="C#" Value="public static string CompressionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string CompressionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.CompressionType" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property CompressionType As String" />
      <MemberSignature Language="F#" Value="member this.CompressionType : string" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.CompressionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23e15-103">シリアライザーで使用される圧縮の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="23e15-103">Gets the compression type used by the serializer.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public static string ContentType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23e15-104">シリアライザーで使用されるコンテンツの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="23e15-104">Gets the content type used by the serializer.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToByteArray">
      <MemberSignature Language="C#" Value="public static byte[] ConvertToByteArray (string telemetryItems, bool compress = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig unsigned int8[] ConvertToByteArray(string telemetryItems, bool compress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.ConvertToByteArray(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ConvertToByteArray (telemetryItems As String, Optional compress As Boolean = true) As Byte()" />
      <MemberSignature Language="F#" Value="static member ConvertToByteArray : string * bool -&gt; byte[]" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.ConvertToByteArray (telemetryItems, compress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Usage", "CA2202:Do not dispose objects multiple times", Justification="Disposing a MemoryStream multiple times is harmless.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetryItems" Type="System.String" />
        <Parameter Name="compress" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="telemetryItems"><span data-ttu-id="23e15-105">製品利用統計情報項目をシリアル化されます。</span><span class="sxs-lookup"><span data-stu-id="23e15-105">Serialized telemetry items.</span></span></param>
        <param name="compress"><span data-ttu-id="23e15-106">シリアル化はまた、圧縮を実行します。</span><span class="sxs-lookup"><span data-stu-id="23e15-106">Should serialization also perform compression.</span></span></param>
        <summary>
            <span data-ttu-id="23e15-107">変換は、バイト配列へのテレメトリ項目をシリアル化されます。</span><span class="sxs-lookup"><span data-stu-id="23e15-107">Converts serialized telemetry items to a byte array.</span></span>
            </summary>
        <returns><span data-ttu-id="23e15-108">圧縮およびシリアル化されたテレメトリ項目。</span><span class="sxs-lookup"><span data-stu-id="23e15-108">The compressed and serialized telemetry items.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deserialize">
      <MemberSignature Language="C#" Value="public static string Deserialize (byte[] telemetryItemsData, bool compress = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string Deserialize(unsigned int8[] telemetryItemsData, bool compress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.Deserialize(System.Byte[],System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Deserialize (telemetryItemsData As Byte(), Optional compress As Boolean = true) As String" />
      <MemberSignature Language="F#" Value="static member Deserialize : byte[] * bool -&gt; string" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.Deserialize (telemetryItemsData, compress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetryItemsData" Type="System.Byte[]" />
        <Parameter Name="compress" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="telemetryItemsData"><span data-ttu-id="23e15-109">製品利用統計情報項目をシリアル化されます。</span><span class="sxs-lookup"><span data-stu-id="23e15-109">Serialized telemetry items.</span></span></param>
        <param name="compress"><span data-ttu-id="23e15-110">逆シリアル化はまた、圧縮解除を実行します。</span><span class="sxs-lookup"><span data-stu-id="23e15-110">Should deserialization also perform decompression.</span></span></param>
        <summary>
            <span data-ttu-id="23e15-111">逆シリアル化し、JSON 文字列を製品利用統計情報項目を解凍します。</span><span class="sxs-lookup"><span data-stu-id="23e15-111">Deserializes and decompress the telemetry items into a JSON string.</span></span>
            </summary>
        <returns><span data-ttu-id="23e15-112">製品利用統計情報項目を文字列としてシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="23e15-112">Telemetry items serialized as a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialize">
      <MemberSignature Language="C#" Value="public static byte[] Serialize (System.Collections.Generic.IEnumerable&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt; telemetryItems, bool compress = true);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig unsigned int8[] Serialize(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ApplicationInsights.Channel.ITelemetry&gt; telemetryItems, bool compress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.Serialize(System.Collections.Generic.IEnumerable{Microsoft.ApplicationInsights.Channel.ITelemetry},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Serialize (telemetryItems As IEnumerable(Of ITelemetry), Optional compress As Boolean = true) As Byte()" />
      <MemberSignature Language="F#" Value="static member Serialize : seq&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt; * bool -&gt; byte[]" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.JsonSerializer.Serialize (telemetryItems, compress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Usage", "CA2202:Do not dispose objects multiple times", Justification="Disposing a MemoryStream multiple times is harmless.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetryItems" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt;" />
        <Parameter Name="compress" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="telemetryItems"><span data-ttu-id="23e15-113">シリアル化する項目を製品利用統計情報の一覧。</span><span class="sxs-lookup"><span data-stu-id="23e15-113">The list of telemetry items to serialize.</span></span></param>
        <param name="compress"><span data-ttu-id="23e15-114">シリアル化はまた、圧縮を実行します。</span><span class="sxs-lookup"><span data-stu-id="23e15-114">Should serialization also perform compression.</span></span></param>
        <summary>
            <span data-ttu-id="23e15-115">シリアル化し、JSON 文字列にテレメトリ項目を圧縮します。</span><span class="sxs-lookup"><span data-stu-id="23e15-115">Serializes and compress the telemetry items into a JSON string.</span></span> <span data-ttu-id="23e15-116">各 JSON オブジェクトは、改行で区切られます。</span><span class="sxs-lookup"><span data-stu-id="23e15-116">Each JSON object is separated by a new line.</span></span> 
            </summary>
        <returns><span data-ttu-id="23e15-117">圧縮およびシリアル化されたテレメトリ項目。</span><span class="sxs-lookup"><span data-stu-id="23e15-117">The compressed and serialized telemetry items.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>