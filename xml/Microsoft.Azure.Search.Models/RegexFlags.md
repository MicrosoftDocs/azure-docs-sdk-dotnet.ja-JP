<Type Name="RegexFlags" FullName="Microsoft.Azure.Search.Models.RegexFlags">
  <TypeSignature Language="C#" Value="public sealed class RegexFlags : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.RegexFlags&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RegexFlags extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.RegexFlags&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.RegexFlags" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RegexFlags&#xA;Inherits ExtensibleEnum(Of RegexFlags)" />
  <TypeSignature Language="F#" Value="type RegexFlags = class&#xA;    inherit ExtensibleEnum&lt;RegexFlags&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.RegexFlags&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.RegexFlags</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.RegexFlags&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="363d8-101">式は、パターン アナライザーとパターン トークナイザで使用する正規を制御する結合できるフラグを定義します。</span><span class="sxs-lookup"><span data-stu-id="363d8-101">Defines flags that can be combined to control how regular expressions are used in the pattern analyzer and pattern tokenizer.</span></span>
            <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#field_summary" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CanonEq">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags CanonEq;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags CanonEq" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.CanonEq" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CanonEq As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable CanonEq : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.CanonEq" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363d8-102">標準的な等価性を有効にします。</span><span class="sxs-lookup"><span data-stu-id="363d8-102">Enables canonical equivalence.</span></span> <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#CANON_EQ" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaseInsensitive">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags CaseInsensitive;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags CaseInsensitive" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.CaseInsensitive" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly CaseInsensitive As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable CaseInsensitive : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.CaseInsensitive" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363d8-103">照合の大文字と小文字を使用できます。</span><span class="sxs-lookup"><span data-stu-id="363d8-103">Enables case-insensitive matching.</span></span> <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#CASE_INSENSITIVE" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Comments">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags Comments;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags Comments" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.Comments" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Comments As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable Comments : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.Comments" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363d8-104">パターンの空白とコメントを許可します。</span><span class="sxs-lookup"><span data-stu-id="363d8-104">Permits whitespace and comments in the pattern.</span></span> <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#COMMENTS" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.RegexFlags Create (string flagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.RegexFlags Create(string flagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.RegexFlags.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (flagExpression As String) As RegexFlags" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.Create flagExpression" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="flagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="flagExpression">
            <span data-ttu-id="363d8-105">正規表現フラグまたは縦棒 (|) で区切られた 2 つ以上のフラグで構成される式の名前。</span><span class="sxs-lookup"><span data-stu-id="363d8-105">Name of the regex flag, or an expression comprised of two or more flags separated by vertical bars (|).</span></span>
            </param>
        <summary>
            <span data-ttu-id="363d8-106">新しい RegexFlags インスタンスを作成または指定された名前と一致する既知の正規表現フラグの場合は、既存のインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="363d8-106">Creates a new RegexFlags instance, or returns an existing instance if the given name matches that of a known regex flag.</span></span>
            </summary>
        <returns><span data-ttu-id="363d8-107">指定された式で RegexFlags インスタンス。</span><span class="sxs-lookup"><span data-stu-id="363d8-107">A RegexFlags instance with the given expression.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DotAll">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags DotAll;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags DotAll" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.DotAll" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DotAll As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable DotAll : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.DotAll" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363d8-108">Dotall モードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="363d8-108">Enables dotall mode.</span></span> <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#DOTALL" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Literal">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags Literal;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags Literal" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.Literal" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Literal As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable Literal : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.Literal" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363d8-109">パターンのリテラルを解析できるようにします。</span><span class="sxs-lookup"><span data-stu-id="363d8-109">Enables literal parsing of the pattern.</span></span> <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#LITERAL" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Multiline">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags Multiline;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags Multiline" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.Multiline" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Multiline As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable Multiline : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.Multiline" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363d8-110">複数行モードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="363d8-110">Enables multiline mode.</span></span> <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#MULTILINE" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_BitwiseOr">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.RegexFlags operator | (Microsoft.Azure.Search.Models.RegexFlags lhs, Microsoft.Azure.Search.Models.RegexFlags rhs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.RegexFlags op_BitwiseOr(class Microsoft.Azure.Search.Models.RegexFlags lhs, class Microsoft.Azure.Search.Models.RegexFlags rhs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.RegexFlags.op_BitwiseOr(Microsoft.Azure.Search.Models.RegexFlags,Microsoft.Azure.Search.Models.RegexFlags)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator Or (lhs As RegexFlags, rhs As RegexFlags) As RegexFlags" />
      <MemberSignature Language="F#" Value="static member ( ||| ) : Microsoft.Azure.Search.Models.RegexFlags * Microsoft.Azure.Search.Models.RegexFlags -&gt; Microsoft.Azure.Search.Models.RegexFlags" Usage="lhs ||| rhs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lhs" Type="Microsoft.Azure.Search.Models.RegexFlags" />
        <Parameter Name="rhs" Type="Microsoft.Azure.Search.Models.RegexFlags" />
      </Parameters>
      <Docs>
        <param name="lhs"><span data-ttu-id="363d8-111">OR 式の左側にあります。</span><span class="sxs-lookup"><span data-stu-id="363d8-111">The left-hand side of the OR expression.</span></span></param>
        <param name="rhs"><span data-ttu-id="363d8-112">OR 式の右側にあります。</span><span class="sxs-lookup"><span data-stu-id="363d8-112">The right-hand side of the OR expression.</span></span></param>
        <summary>
            <span data-ttu-id="363d8-113">ビットごとのオーバー ロードする演算子が 2 つの RegexFlags を結合またはします。</span><span class="sxs-lookup"><span data-stu-id="363d8-113">Overloads the bitwise OR operator to combines two RegexFlags.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="363d8-114">縦棒で区切られた 2 つの指定された RegexFlags を連結した結果である新しい RegexFlags (|)。</span><span class="sxs-lookup"><span data-stu-id="363d8-114">A new RegexFlags that is the result of concatenating the two given RegexFlags, separated by a vertical bar (|).</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.RegexFlags (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.RegexFlags op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.RegexFlags.op_Implicit(System.String)~Microsoft.Azure.Search.Models.RegexFlags" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As RegexFlags" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="363d8-115">変換する文字列。</span><span class="sxs-lookup"><span data-stu-id="363d8-115">string to convert.</span></span></param>
        <summary>
            <span data-ttu-id="363d8-116">文字列から RegexFlags への暗黙的な変換を定義します。</span><span class="sxs-lookup"><span data-stu-id="363d8-116">Defines implicit conversion from string to RegexFlags.</span></span>
            </summary>
        <returns><span data-ttu-id="363d8-117">RegexFlags として文字列です。</span><span class="sxs-lookup"><span data-stu-id="363d8-117">The string as a RegexFlags.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnicodeCase">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags UnicodeCase;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags UnicodeCase" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.UnicodeCase" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly UnicodeCase As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable UnicodeCase : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.UnicodeCase" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363d8-118">Unicode に対応する大文字フォールドを使用できます。</span><span class="sxs-lookup"><span data-stu-id="363d8-118">Enables Unicode-aware case folding.</span></span> <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#UNICODE_CASE" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnixLines">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.RegexFlags UnixLines;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.RegexFlags UnixLines" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.RegexFlags.UnixLines" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly UnixLines As RegexFlags " />
      <MemberSignature Language="F#" Value=" staticval mutable UnixLines : Microsoft.Azure.Search.Models.RegexFlags" Usage="Microsoft.Azure.Search.Models.RegexFlags.UnixLines" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="363d8-119">Unix 行モードを有効にします。</span><span class="sxs-lookup"><span data-stu-id="363d8-119">Enables Unix lines mode.</span></span> <see href="http://docs.oracle.com/javase/6/docs/api/java/util/regex/Pattern.html#UNIX_LINES" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>