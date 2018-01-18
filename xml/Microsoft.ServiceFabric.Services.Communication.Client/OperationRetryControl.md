<Type Name="OperationRetryControl" FullName="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl">
  <TypeSignature Language="C#" Value="public class OperationRetryControl" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationRetryControl extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationRetryControl" />
  <TypeSignature Language="F#" Value="type OperationRetryControl = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9f92a-101">例外の再試行ポリシーが通信にクライアントからサービスを指定します。</span><span class="sxs-lookup"><span data-stu-id="9f92a-101">Specifies the retry policy for the exceptions got on the communication from client to service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationRetryControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.Exception" />
      <MemberSignature Language="VB.NET" Value="Public Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f92a-102">ShouldRetry が false の場合、操作を報告する例外。</span><span class="sxs-lookup"><span data-stu-id="9f92a-102">Exception to report for the operation, if ShouldRetry is false.</span></span> <span data-ttu-id="9f92a-103">既定ではこれは、同じ例外として報告される例外は、場合によっては、ファクトリ可能性があります選択変換を意味のある例外を報告される例外です。</span><span class="sxs-lookup"><span data-stu-id="9f92a-103">By default this is the same exception as the reported exception, however in some cases the Factory may choose to trasform the reported exception to a more meaningful exception.</span></span>
            </summary>
        <value><span data-ttu-id="9f92a-104">例外</span><span class="sxs-lookup"><span data-stu-id="9f92a-104">Exception</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionId">
      <MemberSignature Language="C#" Value="public string ExceptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ExceptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ExceptionId As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionId : string with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ExceptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f92a-105">例外の種類を一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="9f92a-105">String that uniquely identifies the exception type.</span></span>
            </summary>
        <value><span data-ttu-id="9f92a-106">この例外の一意の id。</span><span class="sxs-lookup"><span data-stu-id="9f92a-106">Unique id for this exception.</span></span> <span data-ttu-id="9f92a-107">この id は、この例外は、再試行回数の追跡に使用します。</span><span class="sxs-lookup"><span data-stu-id="9f92a-107">This id is used to keep track of the number of times this exception is retried</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f92a-108">ShouldRetry プロパティが true の場合、このプロパティは、クライアントとサービス間の通信チャネルが有効であるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="9f92a-108">If the ShouldRetry property is true, this property indicates if the communication channel between the client and service is still valid.</span></span>
            <span data-ttu-id="9f92a-109">一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。</span><span class="sxs-lookup"><span data-stu-id="9f92a-109">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="9f92a-110">非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9f92a-110">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9f92a-111">true は、一時的な例外が再試行可能であることを示します。</span><span class="sxs-lookup"><span data-stu-id="9f92a-111">true indicates that this is a transient retriable exception.</span></span>
            <span data-ttu-id="9f92a-112">false は、非一時的な例外が再試行可能であることを示します。</span><span class="sxs-lookup"><span data-stu-id="9f92a-112">false indicates that this is a non transient retriable exception.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f92a-113">最大回数だけ、ShouldRetry が true の場合、この操作を再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9f92a-113">Max number of times this operation should be retried if the ShouldRetry is true</span></span>
            </summary>
        <value><span data-ttu-id="9f92a-114">最大再試行回数</span><span class="sxs-lookup"><span data-stu-id="9f92a-114">Max retry count</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public TimeSpan RetryDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.RetryDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f92a-115">ShouldRetry が true の場合、この遅延後に操作を再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9f92a-115">The operation should be retried after this delay if the ShouldRetry is true.</span></span>
            </summary>
        <value><span data-ttu-id="9f92a-116">操作の再試行するまでの遅延時間</span><span class="sxs-lookup"><span data-stu-id="9f92a-116">Time delay after which the operation should be retried</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ShouldRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ShouldRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property ShouldRetry As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldRetry : bool with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ShouldRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f92a-117">操作を再試行する必要があるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="9f92a-117">Indicates whether the operation should be retried or not.</span></span>
            </summary>
        <value><span data-ttu-id="9f92a-118">ユーザーに、例外をスローする、操作を再試行する場合は true、false の場合</span><span class="sxs-lookup"><span data-stu-id="9f92a-118">true if the operation should be retried, false if the exception should be thrown to the user</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>