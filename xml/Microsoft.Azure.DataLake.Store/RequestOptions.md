<Type Name="RequestOptions" FullName="Microsoft.Azure.DataLake.Store.RequestOptions">
  <TypeSignature Language="C#" Value="public class RequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RequestOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.RequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class RequestOptions" />
  <TypeSignature Language="F#" Value="type RequestOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2d206-101">このクラスには、タイムアウト、再試行ポリシーおよび一意の requestId などの要求パラメーターが含まれています。</span><span class="sxs-lookup"><span data-stu-id="2d206-101">This class contains the request parameters like timeout, Retry Policy and unique requestId</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RequestOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2d206-102">初期化は、GUID、60 秒に、タイムアウトと再試行なしとして要求オプションとして Id を要求します。</span><span class="sxs-lookup"><span data-stu-id="2d206-102">Initializes request Id as GUID, Timeout as 60 seconds, and the request option as No retry</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestOptions (Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy rp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy rp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RequestOptions.#ctor(Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (rp As RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.RequestOptions : Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy -&gt; Microsoft.Azure.DataLake.Store.RequestOptions" Usage="new Microsoft.Azure.DataLake.Store.RequestOptions rp" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rp" Type="Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="rp"><span data-ttu-id="2d206-103">オプションを再試行してください。</span><span class="sxs-lookup"><span data-stu-id="2d206-103">Retry option</span></span></param>
        <summary>
            <span data-ttu-id="2d206-104">初期化します (既定値) の GUID、タイムアウトを 60 秒 (既定)、および要求オプションとして Id を要求します。</span><span class="sxs-lookup"><span data-stu-id="2d206-104">Initializes request Id as GUID (default), Timeout as 60 seconds (default), and the request option</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestOptions (string requestId, TimeSpan timeOut, Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy rp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string requestId, valuetype System.TimeSpan timeOut, class Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy rp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.RequestOptions.#ctor(System.String,System.TimeSpan,Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (requestId As String, timeOut As TimeSpan, rp As RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.RequestOptions : string * TimeSpan * Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy -&gt; Microsoft.Azure.DataLake.Store.RequestOptions" Usage="new Microsoft.Azure.DataLake.Store.RequestOptions (requestId, timeOut, rp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestId" Type="System.String" />
        <Parameter Name="timeOut" Type="System.TimeSpan" />
        <Parameter Name="rp" Type="Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="requestId"><span data-ttu-id="2d206-105">要求 Id</span><span class="sxs-lookup"><span data-stu-id="2d206-105">request Id</span></span></param>
        <param name="timeOut"><span data-ttu-id="2d206-106">タイムアウト</span><span class="sxs-lookup"><span data-stu-id="2d206-106">Time out</span></span></param>
        <param name="rp"><span data-ttu-id="2d206-107">再試行ポリシー</span><span class="sxs-lookup"><span data-stu-id="2d206-107">Retry policy</span></span></param>
        <summary>
            <span data-ttu-id="2d206-108">初期化要求 Id、タイムアウト、および要求オプション</span><span class="sxs-lookup"><span data-stu-id="2d206-108">Initializes request Id, Timeout, and the request option</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.RequestOptions.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.DataLake.Store.RequestOptions.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d206-109">一意の要求の Http 要求の Id</span><span class="sxs-lookup"><span data-stu-id="2d206-109">Unique request Id of the Http Request</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy RetryOption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy RetryOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.RequestOptions.RetryOption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryOption As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryOption : Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy" Usage="Microsoft.Azure.DataLake.Store.RequestOptions.RetryOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.RetryPolicies.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d206-110">使用する再試行ポリシーの種類</span><span class="sxs-lookup"><span data-stu-id="2d206-110">Type of retry policy to use</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeOut">
      <MemberSignature Language="C#" Value="public TimeSpan TimeOut { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.RequestOptions.TimeOut" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeOut As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeOut : TimeSpan with get, set" Usage="Microsoft.Azure.DataLake.Store.RequestOptions.TimeOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d206-111">Http 要求のストリームの読み取りおよび書き込みのタイムアウト</span><span class="sxs-lookup"><span data-stu-id="2d206-111">Timeout for Http request and stream read and write</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>