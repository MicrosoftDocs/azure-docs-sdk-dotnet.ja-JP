<Type Name="EventHubsException" FullName="Microsoft.Azure.EventHubs.EventHubsException">
  <TypeSignature Language="C#" Value="public class EventHubsException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubsException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.EventHubsException" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubsException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type EventHubsException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a7ded-101">Event Hubs のさまざまなエラーの基本例外です。</span><span class="sxs-lookup"><span data-stu-id="a7ded-101">Base Exception for various Event Hubs errors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsException (bool isTransient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isTransient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsException.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isTransient As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsException : bool -&gt; Microsoft.Azure.EventHubs.EventHubsException" Usage="new Microsoft.Azure.EventHubs.EventHubsException isTransient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isTransient" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isTransient"><span data-ttu-id="a7ded-102">例外は一時的なものかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="a7ded-102">Specifies whether or not the exception is transient.</span></span></param>
        <summary>
            <span data-ttu-id="a7ded-103">新しい EventHubsException を返します</span><span class="sxs-lookup"><span data-stu-id="a7ded-103">Returns a new EventHubsException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsException (bool isTransient, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isTransient, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsException.#ctor(System.Boolean,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isTransient As Boolean, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsException : bool * Exception -&gt; Microsoft.Azure.EventHubs.EventHubsException" Usage="new Microsoft.Azure.EventHubs.EventHubsException (isTransient, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="isTransient"><span data-ttu-id="a7ded-104">例外は一時的なものかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="a7ded-104">Specifies whether or not the exception is transient.</span></span></param>
        <param name="innerException"><span data-ttu-id="a7ded-105">内部例外。</span><span class="sxs-lookup"><span data-stu-id="a7ded-105">The inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="a7ded-106">新しい EventHubsException を返します</span><span class="sxs-lookup"><span data-stu-id="a7ded-106">Returns a new EventHubsException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsException (bool isTransient, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isTransient, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsException.#ctor(System.Boolean,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isTransient As Boolean, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsException : bool * string -&gt; Microsoft.Azure.EventHubs.EventHubsException" Usage="new Microsoft.Azure.EventHubs.EventHubsException (isTransient, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isTransient"><span data-ttu-id="a7ded-107">例外は一時的なものかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="a7ded-107">Specifies whether or not the exception is transient.</span></span></param>
        <param name="message"><span data-ttu-id="a7ded-108">詳細なメッセージの例外。</span><span class="sxs-lookup"><span data-stu-id="a7ded-108">The detailed message exception.</span></span></param>
        <summary>
            <span data-ttu-id="a7ded-109">新しい EventHubsException を返します</span><span class="sxs-lookup"><span data-stu-id="a7ded-109">Returns a new EventHubsException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubsException (bool isTransient, string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isTransient, string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.EventHubsException.#ctor(System.Boolean,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isTransient As Boolean, message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.EventHubs.EventHubsException : bool * string * Exception -&gt; Microsoft.Azure.EventHubs.EventHubsException" Usage="new Microsoft.Azure.EventHubs.EventHubsException (isTransient, message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="isTransient"><span data-ttu-id="a7ded-110">例外は一時的なものかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="a7ded-110">Specifies whether or not the exception is transient.</span></span></param>
        <param name="message"><span data-ttu-id="a7ded-111">詳細なメッセージの例外。</span><span class="sxs-lookup"><span data-stu-id="a7ded-111">The detailed message exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="a7ded-112">内部例外。</span><span class="sxs-lookup"><span data-stu-id="a7ded-112">The inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="a7ded-113">新しい EventHubsException を返します</span><span class="sxs-lookup"><span data-stu-id="a7ded-113">Returns a new EventHubsException</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubsNamespace">
      <MemberSignature Language="C#" Value="public string EventHubsNamespace { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubsNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsException.EventHubsNamespace" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubsNamespace As String" />
      <MemberSignature Language="F#" Value="member this.EventHubsNamespace : string" Usage="Microsoft.Azure.EventHubs.EventHubsException.EventHubsNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7ded-114">使用可能な場合は、元の例外が発生した、イベント ハブ名前空間を取得します。</span><span class="sxs-lookup"><span data-stu-id="a7ded-114">Gets the Event Hubs namespace from which the exception occured, if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsException.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool" Usage="Microsoft.Azure.EventHubs.EventHubsException.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7ded-115">例外が、一時的なエラーかを示すブール値。</span><span class="sxs-lookup"><span data-stu-id="a7ded-115">A boolean indicating if the exception is a transient error or not.</span></span>
            </summary>
        <value><span data-ttu-id="a7ded-116">ユーザーがその他の介入なし例外を生成した操作を再試行できる場合に true を返します。</span><span class="sxs-lookup"><span data-stu-id="a7ded-116">returns true when user can retry the operation that generated the exception without additional intervention.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public override string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.EventHubsException.Message" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.EventHubs.EventHubsException.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7ded-117">書式設定された文字列としてメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="a7ded-117">Gets the message as a formatted string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>