<Type Name="LogProfilesOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LogProfilesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LogProfilesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LogProfilesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LogProfilesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8fab7-101">LogProfilesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="8fab7-101">Extension methods for LogProfilesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource CreateOrUpdate (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource CreateOrUpdate(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.String,Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILogProfilesOperations, logProfileName As String, parameters As LogProfileResource) As LogProfileResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * string * Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.CreateOrUpdate (operations, logProfileName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-102">The operations group for this extension method.</span></span>
            </param>
        <param name="logProfileName">
            <span data-ttu-id="8fab7-103">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="8fab7-103">The name of the log profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8fab7-104">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-104">Parameters supplied to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-105">作成または監視の REST API を Azure でログのプロファイルを更新します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-105">Create or update a log profile in Azure Monitoring REST API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.String,Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * string * Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.CreateOrUpdateAsync (operations, logProfileName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-106">The operations group for this extension method.</span></span>
            </param>
        <param name="logProfileName">
            <span data-ttu-id="8fab7-107">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="8fab7-107">The name of the log profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8fab7-108">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-108">Parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fab7-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8fab7-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-110">作成または監視の REST API を Azure でログのプロファイルを更新します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-110">Create or update a log profile in Azure Monitoring REST API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.Delete(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ILogProfilesOperations, logProfileName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.Delete (operations, logProfileName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="logProfileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-111">The operations group for this extension method.</span></span>
            </param>
        <param name="logProfileName">
            <span data-ttu-id="8fab7-112">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="8fab7-112">The name of the log profile.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-113">ログのプロファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-113">Deletes the log profile.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.DeleteAsync (operations, logProfileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-114">The operations group for this extension method.</span></span>
            </param>
        <param name="logProfileName">
            <span data-ttu-id="8fab7-115">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="8fab7-115">The name of the log profile.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fab7-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8fab7-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-117">ログのプロファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-117">Deletes the log profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource Get (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource Get(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.Get(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILogProfilesOperations, logProfileName As String) As LogProfileResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.Get (operations, logProfileName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="logProfileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-118">The operations group for this extension method.</span></span>
            </param>
        <param name="logProfileName">
            <span data-ttu-id="8fab7-119">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="8fab7-119">The name of the log profile.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-120">ログのプロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-120">Gets the log profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt; GetAsync (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt; GetAsync(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.GetAsync (operations, logProfileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-121">The operations group for this extension method.</span></span>
            </param>
        <param name="logProfileName">
            <span data-ttu-id="8fab7-122">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="8fab7-122">The name of the log profile.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fab7-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8fab7-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-124">ログのプロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-124">Gets the log profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt; List (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt; List(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.List(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILogProfilesOperations) As IEnumerable(Of LogProfileResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-125">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-126">ログのプロファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-126">List the log profiles.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-127">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fab7-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8fab7-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-129">ログのプロファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-129">List the log profiles.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource Update (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch logProfilesResource);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource Update(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch logProfilesResource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.Update(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.String,Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ILogProfilesOperations, logProfileName As String, logProfilesResource As LogProfileResourcePatch) As LogProfileResource" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * string * Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.Update (operations, logProfileName, logProfilesResource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="logProfilesResource" Type="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-130">The operations group for this extension method.</span></span>
            </param>
        <param name="logProfileName">
            <span data-ttu-id="8fab7-131">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="8fab7-131">The name of the log profile.</span></span>
            </param>
        <param name="logProfilesResource">
            <span data-ttu-id="8fab7-132">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-132">Parameters supplied to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-133">既存の LogProfilesResource を更新します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-133">Updates an existing LogProfilesResource.</span></span> <span data-ttu-id="8fab7-134">更新するには、その他のフィールドは、CreateOrUpdate メソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-134">To update other fields use the CreateOrUpdate method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt; UpdateAsync (this Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch logProfilesResource, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt; UpdateAsync(class Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations operations, string logProfileName, class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch logProfilesResource, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations,System.String,Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations * string * Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;" Usage="Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions.UpdateAsync (operations, logProfileName, logProfilesResource, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.Management.LogProfilesOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" RefType="this" />
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="logProfilesResource" Type="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8fab7-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8fab7-135">The operations group for this extension method.</span></span>
            </param>
        <param name="logProfileName">
            <span data-ttu-id="8fab7-136">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="8fab7-136">The name of the log profile.</span></span>
            </param>
        <param name="logProfilesResource">
            <span data-ttu-id="8fab7-137">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-137">Parameters supplied to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8fab7-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8fab7-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8fab7-139">既存の LogProfilesResource を更新します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-139">Updates an existing LogProfilesResource.</span></span> <span data-ttu-id="8fab7-140">更新するには、その他のフィールドは、CreateOrUpdate メソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="8fab7-140">To update other fields use the CreateOrUpdate method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>