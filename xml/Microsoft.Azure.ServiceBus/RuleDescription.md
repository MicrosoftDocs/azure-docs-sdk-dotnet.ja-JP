<Type Name="RuleDescription" FullName="Microsoft.Azure.ServiceBus.RuleDescription">
  <TypeSignature Language="C#" Value="public sealed class RuleDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RuleDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.RuleDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RuleDescription" />
  <TypeSignature Language="F#" Value="type RuleDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8a725-101">規則の説明を表します。</span><span class="sxs-lookup"><span data-stu-id="8a725-101">Represents a description of a rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RuleDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8a725-102"><see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" /> クラスの新しいインスタンスを既定値で初期化します。</span><span class="sxs-lookup"><span data-stu-id="8a725-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" /> class with default values.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RuleDescription.#ctor(Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.RuleDescription : Microsoft.Azure.ServiceBus.Filter -&gt; Microsoft.Azure.ServiceBus.RuleDescription" Usage="new Microsoft.Azure.ServiceBus.RuleDescription filter" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filter" Type="Microsoft.Azure.ServiceBus.Filter" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="8a725-103">メッセージと一致するために使用するフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="8a725-103">The filter expression used to match messages.</span></span></param>
        <summary>
            <span data-ttu-id="8a725-104">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" />指定したフィルター式を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="8a725-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" /> class with the specified filter expression.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RuleDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.RuleDescription : string -&gt; Microsoft.Azure.ServiceBus.RuleDescription" Usage="new Microsoft.Azure.ServiceBus.RuleDescription name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>
            <span data-ttu-id="8a725-105">指定した名前を使用して、<see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8a725-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" /> class with the specified name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RuleDescription (string name, Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RuleDescription.#ctor(System.String,Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.RuleDescription : string * Microsoft.Azure.ServiceBus.Filter -&gt; Microsoft.Azure.ServiceBus.RuleDescription" Usage="new Microsoft.Azure.ServiceBus.RuleDescription (name, filter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.Azure.ServiceBus.Filter" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="filter"><span data-ttu-id="8a725-106">メッセージと一致するために使用するフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="8a725-106">The filter expression used to match messages.</span></span></param>
        <summary>
            <span data-ttu-id="8a725-107">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" />指定された名前およびフィルター式を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="8a725-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.ServiceBus.RuleDescription" /> class with the specified name and filter expression.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.RuleAction Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.RuleAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RuleDescription.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As RuleAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.ServiceBus.RuleAction with get, set" Usage="Microsoft.Azure.ServiceBus.RuleDescription.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.RuleAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a725-108">取得またはメッセージがフィルター式を満たす場合に実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="8a725-108">Gets or sets the action to perform if the message satisfies the filtering expression.</span></span>
            </summary>
        <value><span data-ttu-id="8a725-109">メッセージがフィルター式を満たす場合に実行するアクション。</span><span class="sxs-lookup"><span data-stu-id="8a725-109">The action to perform if the message satisfies the filtering expression.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRuleName">
      <MemberSignature Language="C#" Value="public const string DefaultRuleName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultRuleName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultRuleName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultRuleName : string" Usage="Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />
      <MemberType>Field</MemberType>
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
            <span data-ttu-id="8a725-110">サブスクリプションの既定の規則の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="8a725-110">Gets the name of the default rule on the subscription.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="8a725-111">新しいサブスクリプションが作成されると、既定の規則は常に追加します。</span><span class="sxs-lookup"><span data-stu-id="8a725-111">Whenever a new subscription is created, a default rule is always added.</span></span>
            <span data-ttu-id="8a725-112">既定の規則は、<see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />トピック サブスクリプションに到達するすべてのメッセージが有効になります。</span><span class="sxs-lookup"><span data-stu-id="8a725-112">The default rule is a <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> which will enable all messages in the topic to reach subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.Filter Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.ServiceBus.Filter Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RuleDescription.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As Filter" />
      <MemberSignature Language="F#" Value="member this.Filter : Microsoft.Azure.ServiceBus.Filter with get, set" Usage="Microsoft.Azure.ServiceBus.RuleDescription.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Filter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a725-113">取得またはメッセージを照合に使用するフィルター式を設定します。</span><span class="sxs-lookup"><span data-stu-id="8a725-113">Gets or sets the filter expression used to match messages.</span></span>
            </summary>
        <value><span data-ttu-id="8a725-114">メッセージと一致するために使用するフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="8a725-114">The filter expression used to match messages.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="8a725-115">null (Visual Basic では Nothing) が割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="8a725-115">null (Nothing in Visual Basic) is assigned.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RuleDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.ServiceBus.RuleDescription.Name" />
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
            <span data-ttu-id="8a725-116">取得またはルールの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="8a725-116">Gets or sets the name of the rule.</span></span>
            </summary>
        <value><span data-ttu-id="8a725-117">返します、<see cref="T:System.String" />ルールの名前を表すです。</span><span class="sxs-lookup"><span data-stu-id="8a725-117">Returns a <see cref="T:System.String" /> Representing the name of the rule.</span></span></value>
        <remarks><span data-ttu-id="8a725-118">ルール名の最大許容長は、50 文字です。</span><span class="sxs-lookup"><span data-stu-id="8a725-118">Max allowed length of rule name is 50 chars.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>