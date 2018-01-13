<Type Name="SqlFilter" FullName="Microsoft.ServiceBus.Messaging.SqlFilter">
  <TypeSignature Language="C#" Value="public class SqlFilter : Microsoft.ServiceBus.Messaging.Filter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlFilter extends Microsoft.ServiceBus.Messaging.Filter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlFilter&#xA;Inherits Filter" />
  <TypeSignature Language="F#" Value="type SqlFilter = class&#xA;    inherit Filter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.Filter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SqlFilter", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.TrueFilter))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.FalseFilter))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.DateTimeOffset))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="6cd60-101">これは、式の構成フィルターと、パブリッシュ/サブスクライブ パイプラインで実行されるアクションを表します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-101">Represents a filter which is a composition of an expression and an action that is executed in the pub/sub pipeline.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlFilter (string sqlExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SqlFilter : string -&gt; Microsoft.ServiceBus.Messaging.SqlFilter" Usage="new Microsoft.ServiceBus.Messaging.SqlFilter sqlExpression" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlExpression"><span data-ttu-id="6cd60-102">SQL 式です。</span><span class="sxs-lookup"><span data-stu-id="6cd60-102">The SQL expression.</span></span></param>
        <summary><span data-ttu-id="6cd60-103">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.SqlFilter" />クラスの指定の SQL 式を使用します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SqlFilter" /> class using the specified SQL expression.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompatibilityLevel">
      <MemberSignature Language="C#" Value="public int CompatibilityLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CompatibilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlFilter.CompatibilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompatibilityLevel As Integer" />
      <MemberSignature Language="F#" Value="member this.CompatibilityLevel : int" Usage="Microsoft.ServiceBus.Messaging.SqlFilter.CompatibilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="CompatibilityLevel", Order=65538)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6cd60-104">このプロパティは、将来の使用に備えて予約されています。</span><span class="sxs-lookup"><span data-stu-id="6cd60-104">This property is reserved for future use.</span></span> <span data-ttu-id="6cd60-105">互換性レベルを示す整数値現在にハードコード 20 です。</span><span class="sxs-lookup"><span data-stu-id="6cd60-105">An integer value showing the compatibility level, currently hard-coded to 20.</span></span></summary>
        <value><span data-ttu-id="6cd60-106">互換性レベル。</span><span class="sxs-lookup"><span data-stu-id="6cd60-106">The compatibility level.</span></span></value>
        <remarks><span data-ttu-id="6cd60-107">このプロパティは、将来の使用に備えて予約されています。</span><span class="sxs-lookup"><span data-stu-id="6cd60-107">This property is reserved for future use.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public override bool Match (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Match(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlFilter.Match(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Match (message As BrokeredMessage) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Match : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; bool" Usage="sqlFilter.Match message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="6cd60-108">BrokeredMessage です。</span><span class="sxs-lookup"><span data-stu-id="6cd60-108">The BrokeredMessage.</span></span></param>
        <summary><span data-ttu-id="6cd60-109">現在の SQL 式に対して、メッセージが一致するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-109">Specifies whether a message matches against the current SQL expression.</span></span></summary>
        <returns><span data-ttu-id="6cd60-110">現在の SQL 式; に対して truea メッセージに一致します。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="6cd60-110">truea message matches against the current SQL expression; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlFilter.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.SqlFilter.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6cd60-111">フィルター式の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-111">Sets the value of a filter expression.</span></span></summary>
        <value><span data-ttu-id="6cd60-112">フィルター式の値。</span><span class="sxs-lookup"><span data-stu-id="6cd60-112">The value of a filter expression.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.Filter Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.Filter Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlFilter.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Preprocess () As Filter" />
      <MemberSignature Language="F#" Value="override this.Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.Filter" Usage="sqlFilter.Preprocess " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Filter</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6cd60-113">プリプロセス済みのフィルター式を取得します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-113">Gets the preprocessed filter expression.</span></span></summary>
        <returns><span data-ttu-id="6cd60-114">プリプロセス済みのフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="6cd60-114">The preprocessed filter expression.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public override bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlFilter.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.SqlFilter.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6cd60-115">SQL フィルター式の前処理が必要かどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-115">Gets a value indicating whether the SQL filter expression requires preprocessing.</span></span></summary>
        <value><span data-ttu-id="6cd60-116">true の場合は、SQL フィルター式では、前処理; が必要です。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="6cd60-116">true if the SQL filter expression requires preprocessing; otherwise, false.</span></span> <span data-ttu-id="6cd60-117">現在常に true を返します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-117">Currently always returns true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlFilter.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string" Usage="Microsoft.ServiceBus.Messaging.SqlFilter.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="SqlExpression", Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6cd60-118">SQL 式を取得します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-118">Gets the SQL expression.</span></span></summary>
        <value><span data-ttu-id="6cd60-119">SQL 式です。</span><span class="sxs-lookup"><span data-stu-id="6cd60-119">The SQL expression.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="sqlFilter.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6cd60-120">文字列表現を返します<see cref="T:Microsoft.ServiceBus.Messaging.SqlFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="6cd60-120">Returns a string representation of <see cref="T:Microsoft.ServiceBus.Messaging.SqlFilter" />.</span></span></summary>
        <returns><span data-ttu-id="6cd60-121"><see cref="T:Microsoft.ServiceBus.Messaging.SqlFilter" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="6cd60-121">The string representation of <see cref="T:Microsoft.ServiceBus.Messaging.SqlFilter" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sqlFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6cd60-122">SQL 式を検証します。</span><span class="sxs-lookup"><span data-stu-id="6cd60-122">Validates the SQL expression.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>