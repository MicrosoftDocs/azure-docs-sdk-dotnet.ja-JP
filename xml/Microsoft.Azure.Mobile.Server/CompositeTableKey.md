<Type Name="CompositeTableKey" FullName="Microsoft.Azure.Mobile.Server.CompositeTableKey">
  <TypeSignature Language="C#" Value="public class CompositeTableKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CompositeTableKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />
  <TypeSignature Language="VB.NET" Value="Public Class CompositeTableKey" />
  <TypeSignature Language="F#" Value="type CompositeTableKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="74bc9-101">A<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />テーブル内の単一行の識別に使用される 1 つまたは複数のキーが含まれています。</span><span class="sxs-lookup"><span data-stu-id="74bc9-101">A <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> contains one or more keys used to identify a single row in a table.</span></span>
            <span data-ttu-id="74bc9-102">文字列の形式、<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />必要に応じて 1 つの引用符で囲まれた用語の (LWS) なしのコンマ区切りリストです。</span><span class="sxs-lookup"><span data-stu-id="74bc9-102">The string format of a <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> is a comma separated list (without LWS) of optionally single-quoted terms.</span></span>
            <span data-ttu-id="74bc9-103">コンマが含まれている場合に引用符で囲む、条項があるだけです。</span><span class="sxs-lookup"><span data-stu-id="74bc9-103">The terms only have to be quoted if they contain a comma.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CompositeTableKey (params string[] segments);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] segments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray segments As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.CompositeTableKey : string[] -&gt; Microsoft.Azure.Mobile.Server.CompositeTableKey" Usage="new Microsoft.Azure.Mobile.Server.CompositeTableKey segments" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="segments" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="segments"><span data-ttu-id="74bc9-104">順序付けされたセット<see cref="T:System.String" />セグメントを複合キーを作成します。</span><span class="sxs-lookup"><span data-stu-id="74bc9-104">The ordered set of <see cref="T:System.String" /> segments making up the composite key.</span></span></param>
        <summary>
            <span data-ttu-id="74bc9-105">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />で指定された数の<see cref="T:System.String" />複合キーを構成するセグメントの順序付きリストを表すです。</span><span class="sxs-lookup"><span data-stu-id="74bc9-105">Initialize a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> with a given number of <see cref="T:System.String" /> representing an ordered list of segments making up the composite key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parse">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Mobile.Server.CompositeTableKey Parse (string tableKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Mobile.Server.CompositeTableKey Parse(string tableKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.Parse(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Parse (tableKey As String) As CompositeTableKey" />
      <MemberSignature Language="F#" Value="static member Parse : string -&gt; Microsoft.Azure.Mobile.Server.CompositeTableKey" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.Parse tableKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.CompositeTableKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableKey"><span data-ttu-id="74bc9-106">複合キーを含む値です。</span><span class="sxs-lookup"><span data-stu-id="74bc9-106">The value containing the composite key.</span></span></param>
        <summary>
            <span data-ttu-id="74bc9-107">として文字列を解析する<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />です。</span><span class="sxs-lookup"><span data-stu-id="74bc9-107">Parse a string as a <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />.</span></span> <span data-ttu-id="74bc9-108">必要に応じて 1 つの引用符で囲まれた用語の (LWS) なしのコンマ区切りリストにするのには、値がします。</span><span class="sxs-lookup"><span data-stu-id="74bc9-108">The value has to be a comma separated list (without LWS) of optionally single-quoted terms.</span></span>
            <span data-ttu-id="74bc9-109">値が有効でない場合、<see cref="T:System.ArgumentException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="74bc9-109">If the value is not valid then an <see cref="T:System.ArgumentException" /> is thrown.</span></span>
            </summary>
        <returns><span data-ttu-id="74bc9-110">新しい <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> インスタンス。</span><span class="sxs-lookup"><span data-stu-id="74bc9-110">A new <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Segments">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; Segments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; Segments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.CompositeTableKey.Segments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Segments As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.Segments : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.Segments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="74bc9-111">取得、順序付けられた<see cref="T:System.Collections.ObjectModel.Collection`1" />セグメントの複合キーを構成するのです。</span><span class="sxs-lookup"><span data-stu-id="74bc9-111">Gets the ordered <see cref="T:System.Collections.ObjectModel.Collection`1" /> of segments making up the composite key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="compositeTableKey.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="74bc9-112">生成、<see cref="T:System.String" />複合キーの形式です。</span><span class="sxs-lookup"><span data-stu-id="74bc9-112">Generates a <see cref="T:System.String" /> representation of the composite key.</span></span>
            </summary>
        <returns><span data-ttu-id="74bc9-113">A<see cref="T:System.String" />複合キーの形式です。</span><span class="sxs-lookup"><span data-stu-id="74bc9-113">A <see cref="T:System.String" /> representation of the composite key.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParse">
      <MemberSignature Language="C#" Value="public static bool TryParse (string tableKey, out Microsoft.Azure.Mobile.Server.CompositeTableKey compositeTableKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParse(string tableKey, [out] class Microsoft.Azure.Mobile.Server.CompositeTableKey&amp; compositeTableKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.CompositeTableKey.TryParse(System.String,Microsoft.Azure.Mobile.Server.CompositeTableKey@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParse (tableKey As String, ByRef compositeTableKey As CompositeTableKey) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParse : string *  -&gt; bool" Usage="Microsoft.Azure.Mobile.Server.CompositeTableKey.TryParse (tableKey, compositeTableKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableKey" Type="System.String" />
        <Parameter Name="compositeTableKey" Type="Microsoft.Azure.Mobile.Server.CompositeTableKey&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="tableKey"><span data-ttu-id="74bc9-114">複合キーを含む値です。</span><span class="sxs-lookup"><span data-stu-id="74bc9-114">The value containing the composite key.</span></span></param>
        <param name="compositeTableKey"><span data-ttu-id="74bc9-115">メソッドを返す場合<c>true</c>し<paramref name="compositeTableKey" />結果を含むです。 それ以外の場合<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="74bc9-115">If the method returns <c>true</c> then <paramref name="compositeTableKey" /> contains the result; otherwise <c>null</c>.</span></span></param>
        <summary>
            <span data-ttu-id="74bc9-116">新たに作成する試行<see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" />から、指定された<paramref name="tableKey" />です。</span><span class="sxs-lookup"><span data-stu-id="74bc9-116">Attempts creating a new <see cref="T:Microsoft.Azure.Mobile.Server.CompositeTableKey" /> from a given <paramref name="tableKey" />.</span></span>
            <span data-ttu-id="74bc9-117">戻り値は、かどうか、解析が成功したことを示します。</span><span class="sxs-lookup"><span data-stu-id="74bc9-117">The return value indicates whether the parsing succeeded.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>