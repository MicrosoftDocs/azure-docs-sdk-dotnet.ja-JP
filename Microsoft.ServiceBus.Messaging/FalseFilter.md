<Type Name="FalseFilter" FullName="Microsoft.ServiceBus.Messaging.FalseFilter">
  <TypeSignature Language="C#" Value="public sealed class FalseFilter : Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FalseFilter extends Microsoft.ServiceBus.Messaging.SqlFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.FalseFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FalseFilter&#xA;Inherits SqlFilter" />
  <TypeSignature Language="F#" Value="type FalseFilter = class&#xA;    inherit SqlFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.SqlFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="FalseFilter", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="c5cd8-101">False のフィルター式を表します。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-101">Represents the false filter expression.</span></span></summary>
    <remarks><span data-ttu-id="c5cd8-102">最初にすべてのメッセージをブロックするサブスクリプションを作成する場合は、一致なしの式を使用してください。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-102">The Match None expression should be used if you want to create a subscription that initially block all messages.</span></span> <span data-ttu-id="c5cd8-103">通常このシナリオをサブスクリプションを作成しますが、後でこのサブスクリプションを有効にする場合です。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-103">Typically in this scenario is you may want to create the subscription but want to enable this subscription at a later date.</span></span> <span data-ttu-id="c5cd8-104">このフィルターは、そのシナリオを有効になります。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-104">This filter will enable that scenario.</span></span> </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FalseFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="c5cd8-105"><see cref="T:Microsoft.ServiceBus.Messaging.FalseFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.FalseFilter" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public override bool Match (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Match(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Match(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Match (message As BrokeredMessage) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Match : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; bool" Usage="falseFilter.Match message" />
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
        <param name="message"><span data-ttu-id="c5cd8-106">仲介型メッセージです。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-106">The brokered message.</span></span></param>
        <summary><span data-ttu-id="c5cd8-107">現在の SQL 式に対してメッセージと一致します。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-107">Matches a message against the current SQL expression.</span></span></summary>
        <returns><span data-ttu-id="c5cd8-108">に一致する場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-108">true if it matches; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.Filter Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.Filter Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Preprocess () As Filter" />
      <MemberSignature Language="F#" Value="override this.Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.Filter" Usage="falseFilter.Preprocess " />
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
        <summary><span data-ttu-id="c5cd8-109">プリプロセス済みのフィルター式を取得します。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-109">Gets the preprocessed filter expression.</span></span></summary>
        <returns><span data-ttu-id="c5cd8-110">プリプロセス済みのフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-110">The preprocessed filter expression.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public override bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.FalseFilter.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.FalseFilter.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c5cd8-111">SQL フィルター式の前処理が必要かどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-111">Gets a value indicating whether the SQL filter expression requires preprocessing.</span></span></summary>
        <value><span data-ttu-id="c5cd8-112">true の場合は、SQL フィルター式では、前処理; が必要です。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-112">true if the SQL filter expression requires preprocessing; otherwise, false.</span></span> <span data-ttu-id="c5cd8-113">現在常に true を返します。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-113">Currently always returns true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="falseFilter.ToString " />
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
        <summary><span data-ttu-id="c5cd8-114">現在のインスタンスを文字列形式に変換します。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-114">Converts the current instance to its string representation.</span></span></summary>
        <returns><span data-ttu-id="c5cd8-115">現在のインスタンスの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-115">A string representation of the current instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.FalseFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="falseFilter.Validate " />
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
        <summary><span data-ttu-id="c5cd8-116">SQL 式を検証します。</span><span class="sxs-lookup"><span data-stu-id="c5cd8-116">Validates the SQL expression.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>