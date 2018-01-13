<Type Name="DataType" FullName="Microsoft.Azure.Search.Models.DataType">
  <TypeSignature Language="C#" Value="public sealed class DataType : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.DataType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataType extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.DataType&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataType&#xA;Inherits ExtensibleEnum(Of DataType)" />
  <TypeSignature Language="F#" Value="type DataType = class&#xA;    inherit ExtensibleEnum&lt;DataType&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.DataType&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.DataType</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.DataType&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="91f70-101">Azure Search インデックスには、フィールドのデータ型を定義します。</span><span class="sxs-lookup"><span data-stu-id="91f70-101">Defines the data type of a field in an Azure Search index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Boolean">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Boolean;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Boolean" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Boolean" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Boolean As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Boolean : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Boolean" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91f70-102">フィールドに、ブール値 (true または false) が含まれていることを示します。</span><span class="sxs-lookup"><span data-stu-id="91f70-102">Indicates that a field contains a Boolean value (true or false).</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataType Collection (Microsoft.Azure.Search.Models.DataType elementType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataType Collection(class Microsoft.Azure.Search.Models.DataType elementType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.Collection(Microsoft.Azure.Search.Models.DataType)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Collection (elementType As DataType) As DataType" />
      <MemberSignature Language="F#" Value="static member Collection : Microsoft.Azure.Search.Models.DataType -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Collection elementType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elementType" Type="Microsoft.Azure.Search.Models.DataType" />
      </Parameters>
      <Docs>
        <param name="elementType"><span data-ttu-id="91f70-103">コレクションの要素のデータ型です。</span><span class="sxs-lookup"><span data-stu-id="91f70-103">The DataType of the elements of the collection.</span></span></param>
        <summary>
            <span data-ttu-id="91f70-104">指定された型のコレクションのデータ型を作成します。</span><span class="sxs-lookup"><span data-stu-id="91f70-104">Creates a DataType for a collection of the given type.</span></span>
            </summary>
        <returns><span data-ttu-id="91f70-105">コレクションの新しいデータ型です。</span><span class="sxs-lookup"><span data-stu-id="91f70-105">A new DataType for a collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataType Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataType Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As DataType" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="91f70-106">データ型の名前です。</span><span class="sxs-lookup"><span data-stu-id="91f70-106">Name of the data type.</span></span></param>
        <summary>
            <span data-ttu-id="91f70-107">新しいデータ型インスタンスを作成または指定された名前と一致する既知のデータ型の場合は、既存のインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="91f70-107">Creates a new DataType instance, or returns an existing instance if the given name matches that of a known data type.</span></span>
            </summary>
        <returns><span data-ttu-id="91f70-108">指定した名前のデータ型のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="91f70-108">A DataType instance with the given name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateTimeOffset">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType DateTimeOffset;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType DateTimeOffset" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.DateTimeOffset" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DateTimeOffset As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable DateTimeOffset : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.DateTimeOffset" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91f70-109">フィールドにタイム ゾーン情報を含む、日付/時刻値が含まれていることを示します。</span><span class="sxs-lookup"><span data-stu-id="91f70-109">Indicates that a field contains a date/time value, including timezone information.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Double">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Double;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Double" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Double" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Double As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Double : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Double" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91f70-110">フィールドに、IEEE 倍精度浮動小数点数が含まれていることを示します。</span><span class="sxs-lookup"><span data-stu-id="91f70-110">Indicates that a field contains an IEEE double-precision floating point number.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeographyPoint">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType GeographyPoint;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType GeographyPoint" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.GeographyPoint" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly GeographyPoint As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable GeographyPoint : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.GeographyPoint" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91f70-111">フィールドが経度と緯度の観点からは、地理的な場所が含まれていることを示します。</span><span class="sxs-lookup"><span data-stu-id="91f70-111">Indicates that a field contains a geo-location in terms of longitude and latitude.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Int32">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Int32;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Int32" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Int32" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Int32 As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Int32 : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Int32" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91f70-112">フィールドが 32 ビット符号付き整数が含まれていることを示します。</span><span class="sxs-lookup"><span data-stu-id="91f70-112">Indicates that a field contains a 32-bit signed integer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Int64">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Int64;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Int64" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Int64" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Int64 As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Int64 : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Int64" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91f70-113">フィールドに、64 ビット符号付き整数が含まれていることを示します。</span><span class="sxs-lookup"><span data-stu-id="91f70-113">Indicates that a field contains a 64-bit signed integer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.DataType (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.DataType op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.op_Implicit(System.String)~Microsoft.Azure.Search.Models.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As DataType" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="91f70-114">変換する文字列。</span><span class="sxs-lookup"><span data-stu-id="91f70-114">string to convert.</span></span></param>
        <summary>
            <span data-ttu-id="91f70-115">文字列からのデータ型への暗黙的な変換を定義します。</span><span class="sxs-lookup"><span data-stu-id="91f70-115">Defines implicit conversion from string to DataType.</span></span>
            </summary>
        <returns><span data-ttu-id="91f70-116">データ型としての文字列。</span><span class="sxs-lookup"><span data-stu-id="91f70-116">The string as a DataType.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="String">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType String;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType String" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.String" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly String As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable String : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.String" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91f70-117">フィールドに文字列が含まれていることを示します。</span><span class="sxs-lookup"><span data-stu-id="91f70-117">Indicates that a field contains a string.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>