<Type Name="UsersOperationsExtensions" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0d04f-101">UsersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="0d04f-101">Extension methods for UsersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; CreateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; CreateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.CreateAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d04f-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0d04f-103">ユーザーを作成するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-103">Parameters to create a user.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d04f-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d04f-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d04f-105">新しいユーザーを作成します。</span><span class="sxs-lookup"><span data-stu-id="0d04f-105">Create a new user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.DeleteAsync (operations, upnOrObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="upnOrObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d04f-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-106">The operations group for this extension method.</span></span>
            </param>
        <param name="upnOrObjectId">
            <span data-ttu-id="0d04f-107">削除するオブジェクト ID またはユーザーのプリンシパルの名前。</span><span class="sxs-lookup"><span data-stu-id="0d04f-107">The object ID or principal name of the user to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d04f-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d04f-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d04f-109">ユーザーを削除します。</span><span class="sxs-lookup"><span data-stu-id="0d04f-109">Delete a user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; GetAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; GetAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.GetAsync (operations, upnOrObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="upnOrObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d04f-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-110">The operations group for this extension method.</span></span>
            </param>
        <param name="upnOrObjectId">
            <span data-ttu-id="0d04f-111">オブジェクト ID または情報を取得する対象のユーザーのプリンシパル名。</span><span class="sxs-lookup"><span data-stu-id="0d04f-111">The object ID or principal name of the user for which to get information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d04f-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d04f-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d04f-113">ディレクトリからユーザー情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d04f-113">Gets user information from the directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMemberGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetMemberGroupsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string objectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetMemberGroupsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string objectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.GetMemberGroupsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMemberGroupsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.GetMemberGroupsAsync (operations, objectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;GetMemberGroupsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d04f-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-114">The operations group for this extension method.</span></span>
            </param>
        <param name="objectId">
            <span data-ttu-id="0d04f-115">グループ メンバーシップを取得する対象のユーザーのオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="0d04f-115">The object ID of the user for which to get group membership.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0d04f-116">ユーザー フィルターのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-116">User filtering parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d04f-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d04f-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d04f-118">ユーザーがメンバーになっているグループのオブジェクト Id を含むコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="0d04f-118">Gets a collection that contains the object IDs of the groups of which the user is a member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d04f-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-119">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="0d04f-120">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="0d04f-120">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d04f-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d04f-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d04f-122">現在のテナントのユーザーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d04f-122">Gets list of users for the current tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.ListNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d04f-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-123">The operations group for this extension method.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="0d04f-124">一覧表示操作の次のリンク。</span><span class="sxs-lookup"><span data-stu-id="0d04f-124">Next link for the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d04f-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d04f-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d04f-126">現在のテナントのユーザーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0d04f-126">Gets a list of users for the current tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.UpdateAsync (operations, upnOrObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="upnOrObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0d04f-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-127">The operations group for this extension method.</span></span>
            </param>
        <param name="upnOrObjectId">
            <span data-ttu-id="0d04f-128">更新するオブジェクト ID またはユーザーのプリンシパルの名前。</span><span class="sxs-lookup"><span data-stu-id="0d04f-128">The object ID or principal name of the user to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0d04f-129">既存のユーザーを更新するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0d04f-129">Parameters to update an existing user.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d04f-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d04f-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d04f-131">ユーザーを更新します。</span><span class="sxs-lookup"><span data-stu-id="0d04f-131">Updates a user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>