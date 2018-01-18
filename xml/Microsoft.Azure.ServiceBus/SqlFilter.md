<Type Name="SqlFilter" FullName="Microsoft.Azure.ServiceBus.SqlFilter">
  <TypeSignature Language="C#" Value="public class SqlFilter : Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlFilter extends Microsoft.Azure.ServiceBus.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SqlFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type SqlFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="89ee2-101">これは、式の構成フィルターと、パブリッシュ/サブスクライブ パイプラインで実行されるアクションを表します。</span><span class="sxs-lookup"><span data-stu-id="89ee2-101">Represents a filter which is a composition of an expression and an action that is executed in the pub/sub pipeline.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="89ee2-102">A<see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />到着するメッセージのユーザー定義のプロパティとシステムのプロパティに対して、ブローカーで評価される SQL のような条件式を保持します。</span><span class="sxs-lookup"><span data-stu-id="89ee2-102">A <see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" /> holds a SQL-like condition expression that is evaluated in the broker against the arriving messages' user-defined properties and system properties.</span></span> <span data-ttu-id="89ee2-103">すべてのシステム プロパティ (すべてのプロパティに明示的に示すで、<see cref="T:Microsoft.Azure.ServiceBus.Message" />クラス) を付ける必要があります<code>sys.</code>条件式にします。</span><span class="sxs-lookup"><span data-stu-id="89ee2-103">All system properties (which are all properties explicitly listed on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /> class) must be prefixed with <code>sys.</code> in the condition expression.</span></span> <span data-ttu-id="89ee2-104">SQL のサブセットを実装 (EXISTS) のプロパティの存在をテスト、null 値 (IS NULL)、論理 NOT/AND または OR、テスト関係演算子、数値の算術演算で単純なテキストのパターンを LIKE で一致します。</span><span class="sxs-lookup"><span data-stu-id="89ee2-104">The SQL subset implements testing for existence of properties (EXISTS), testing for null-values (IS NULL), logical NOT/AND/OR, relational operators, numeric arithmetic, and simple text pattern matching with LIKE.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlFilter (string sqlExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SqlFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SqlFilter : string -&gt; Microsoft.Azure.ServiceBus.SqlFilter" Usage="new Microsoft.Azure.ServiceBus.SqlFilter sqlExpression" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">To be added.</param>
        <summary>
            <span data-ttu-id="89ee2-105">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />クラスの指定の SQL 式を使用します。</span><span class="sxs-lookup"><span data-stu-id="89ee2-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" /> class using the specified SQL expression.</span></span>
            </summary>
        <remarks><span data-ttu-id="89ee2-106">Sql 式の最大許容長は、1024 文字です。</span><span class="sxs-lookup"><span data-stu-id="89ee2-106">Max allowed length of sql expression is 1024 chars.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SqlFilter.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.SqlFilter.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89ee2-107">フィルター式の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="89ee2-107">Sets the value of a filter expression.</span></span>
            </summary>
        <value><span data-ttu-id="89ee2-108">フィルター式の値。</span><span class="sxs-lookup"><span data-stu-id="89ee2-108">The value of a filter expression.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SqlFilter.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string" Usage="Microsoft.Azure.ServiceBus.SqlFilter.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="89ee2-109">SQL 式を取得します。</span><span class="sxs-lookup"><span data-stu-id="89ee2-109">Gets the SQL expression.</span></span>
            </summary>
        <value><span data-ttu-id="89ee2-110">SQL 式です。</span><span class="sxs-lookup"><span data-stu-id="89ee2-110">The SQL expression.</span></span></value>
        <remarks><span data-ttu-id="89ee2-111">Sql 式の最大許容長は、1024 文字です。</span><span class="sxs-lookup"><span data-stu-id="89ee2-111">Max allowed length of sql expression is 1024 chars.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SqlFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="sqlFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="89ee2-112">文字列表現を返します<see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="89ee2-112">Returns a string representation of <see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />.</span></span>
            </summary>
        <returns><span data-ttu-id="89ee2-113"><see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="89ee2-113">The string representation of <see cref="T:Microsoft.Azure.ServiceBus.SqlFilter" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>