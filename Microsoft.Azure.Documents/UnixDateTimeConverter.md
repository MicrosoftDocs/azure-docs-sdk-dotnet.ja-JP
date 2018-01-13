<Type Name="UnixDateTimeConverter" FullName="Microsoft.Azure.Documents.UnixDateTimeConverter">
  <TypeSignature Language="C#" Value="public sealed class UnixDateTimeConverter : Newtonsoft.Json.Converters.DateTimeConverterBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UnixDateTimeConverter extends Newtonsoft.Json.Converters.DateTimeConverterBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.UnixDateTimeConverter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UnixDateTimeConverter&#xA;Inherits DateTimeConverterBase" />
  <TypeSignature Language="F#" Value="type UnixDateTimeConverter = class&#xA;    inherit DateTimeConverterBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.Converters.DateTimeConverterBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f430f-101">JSON との間、DateTime オブジェクトに変換します。</span><span class="sxs-lookup"><span data-stu-id="f430f-101">Converts a DateTime object to and from JSON.</span></span>
            <span data-ttu-id="f430f-102">合計 (午前 0 時 (utc)/GMT)、1970 年 1 月 1 日から経過した秒数として表される DateTime うるう秒をカウントしない (iso 8601: 1970-01-01T00:00:00Z)。</span><span class="sxs-lookup"><span data-stu-id="f430f-102">DateTime is represented as the total number of seconds that have elapsed since January 1, 1970 (midnight UTC/GMT), not counting leap seconds (in ISO 8601: 1970-01-01T00:00:00Z).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UnixDateTimeConverter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.UnixDateTimeConverter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadJson">
      <MemberSignature Language="C#" Value="public override object ReadJson (Newtonsoft.Json.JsonReader reader, Type objectType, object existingValue, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance object ReadJson(class Newtonsoft.Json.JsonReader reader, class System.Type objectType, object existingValue, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.UnixDateTimeConverter.ReadJson(Newtonsoft.Json.JsonReader,System.Type,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadJson (reader As JsonReader, objectType As Type, existingValue As Object, serializer As JsonSerializer) As Object" />
      <MemberSignature Language="F#" Value="override this.ReadJson : Newtonsoft.Json.JsonReader * Type * obj * Newtonsoft.Json.JsonSerializer -&gt; obj" Usage="unixDateTimeConverter.ReadJson (reader, objectType, existingValue, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="objectType" Type="System.Type" />
        <Parameter Name="existingValue" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="reader"><span data-ttu-id="f430f-103">読み取りに Newtonsoft.Json.JsonReader です。</span><span class="sxs-lookup"><span data-stu-id="f430f-103">The Newtonsoft.Json.JsonReader to read from.</span></span></param>
        <param name="objectType"><span data-ttu-id="f430f-104">オブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="f430f-104">Type of the object.</span></span></param>
        <param name="existingValue"><span data-ttu-id="f430f-105">読み取られるオブジェクトの既存の値。</span><span class="sxs-lookup"><span data-stu-id="f430f-105">The existing value of object being read.</span></span></param>
        <param name="serializer"><span data-ttu-id="f430f-106">呼び出し元のシリアライザー。</span><span class="sxs-lookup"><span data-stu-id="f430f-106">The calling serializer.</span></span></param>
        <summary>
            <span data-ttu-id="f430f-107">DateTime オブジェクトの JSON 表現を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="f430f-107">Reads the JSON representation of the DateTime object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f430f-108">DateTime オブジェクトの値。</span><span class="sxs-lookup"><span data-stu-id="f430f-108">The DateTime object value.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteJson">
      <MemberSignature Language="C#" Value="public override void WriteJson (Newtonsoft.Json.JsonWriter writer, object value, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void WriteJson(class Newtonsoft.Json.JsonWriter writer, object value, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.UnixDateTimeConverter.WriteJson(Newtonsoft.Json.JsonWriter,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub WriteJson (writer As JsonWriter, value As Object, serializer As JsonSerializer)" />
      <MemberSignature Language="F#" Value="override this.WriteJson : Newtonsoft.Json.JsonWriter * obj * Newtonsoft.Json.JsonSerializer -&gt; unit" Usage="unixDateTimeConverter.WriteJson (writer, value, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="Newtonsoft.Json.JsonWriter" />
        <Parameter Name="value" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="writer"><span data-ttu-id="f430f-109">書き込む Newtonsoft.Json.JsonWriter です。</span><span class="sxs-lookup"><span data-stu-id="f430f-109">The Newtonsoft.Json.JsonWriter to write to.</span></span></param>
        <param name="value"><span data-ttu-id="f430f-110">値。</span><span class="sxs-lookup"><span data-stu-id="f430f-110">The value.</span></span></param>
        <param name="serializer"><span data-ttu-id="f430f-111">呼び出し元のシリアライザー。</span><span class="sxs-lookup"><span data-stu-id="f430f-111">The calling serializer.</span></span></param>
        <summary>
            <span data-ttu-id="f430f-112">DateTime オブジェクトの JSON 表現を書き込みます。</span><span class="sxs-lookup"><span data-stu-id="f430f-112">Writes the JSON representation of the DateTime object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>