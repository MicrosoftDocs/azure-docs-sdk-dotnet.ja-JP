<Type Name="TagsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TagsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TagsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TagsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TagsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7c293-101">TagsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7c293-101">Extension methods for TagsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.TagDetails CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.TagDetails CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITagsOperations, tagName As String) As TagDetails" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.TagDetails" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdate (operations, tagName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TagDetails</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-102">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="7c293-103">作成するタグの名前。</span><span class="sxs-lookup"><span data-stu-id="7c293-103">The name of the tag to create.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-104">サブスクリプションにタグを作成します。</span><span class="sxs-lookup"><span data-stu-id="7c293-104">Creates a tag in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c293-105">タグ名は、512 文字までの最大値を持つことができ、大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7c293-105">The tag name can have a maximum of 512 characters and is case insensitive.</span></span>
            <span data-ttu-id="7c293-106">Azure によって作成されたタグ名には、microsoft、azure、または windows のプレフィックスがあります。</span><span class="sxs-lookup"><span data-stu-id="7c293-106">Tag names created by Azure have prefixes of microsoft, azure, or windows.</span></span>
            <span data-ttu-id="7c293-107">これらのプレフィックスのいずれかのタグを作成することはできません。</span><span class="sxs-lookup"><span data-stu-id="7c293-107">You cannot create tags with one of these prefixes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateAsync (operations, tagName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-108">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="7c293-109">作成するタグの名前。</span><span class="sxs-lookup"><span data-stu-id="7c293-109">The name of the tag to create.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c293-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c293-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-111">サブスクリプションにタグを作成します。</span><span class="sxs-lookup"><span data-stu-id="7c293-111">Creates a tag in the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c293-112">タグ名は、512 文字までの最大値を持つことができ、大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7c293-112">The tag name can have a maximum of 512 characters and is case insensitive.</span></span>
            <span data-ttu-id="7c293-113">Azure によって作成されたタグ名には、microsoft、azure、または windows のプレフィックスがあります。</span><span class="sxs-lookup"><span data-stu-id="7c293-113">Tag names created by Azure have prefixes of microsoft, azure, or windows.</span></span>
            <span data-ttu-id="7c293-114">これらのプレフィックスのいずれかのタグを作成することはできません。</span><span class="sxs-lookup"><span data-stu-id="7c293-114">You cannot create tags with one of these prefixes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateValue">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.TagValue CreateOrUpdateValue (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.TagValue CreateOrUpdateValue(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateValue(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateValue : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.TagValue" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateValue (operations, tagName, tagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.TagValue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-115">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="7c293-116">タグの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c293-116">The name of the tag.</span></span>
            </param>
        <param name="tagValue">
            <span data-ttu-id="7c293-117">作成するタグの値。</span><span class="sxs-lookup"><span data-stu-id="7c293-117">The value of the tag to create.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-118">タグの値を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c293-118">Creates a tag value.</span></span> <span data-ttu-id="7c293-119">タグの名前は既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c293-119">The name of the tag must already exist.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateValueAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; CreateOrUpdateValueAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt; CreateOrUpdateValueAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateValueAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateValueAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.CreateOrUpdateValueAsync (operations, tagName, tagValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;CreateOrUpdateValueAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.TagValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-120">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="7c293-121">タグの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c293-121">The name of the tag.</span></span>
            </param>
        <param name="tagValue">
            <span data-ttu-id="7c293-122">作成するタグの値。</span><span class="sxs-lookup"><span data-stu-id="7c293-122">The value of the tag to create.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c293-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c293-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-124">タグの値を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c293-124">Creates a tag value.</span></span> <span data-ttu-id="7c293-125">タグの名前は既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c293-125">The name of the tag must already exist.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITagsOperations, tagName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.Delete (operations, tagName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-126">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="7c293-127">タグの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c293-127">The name of the tag.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-128">サブスクリプションからタグを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c293-128">Deletes a tag from the subscription.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="7c293-129">削除する前に、リソース タグからすべての値を削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c293-129">You must remove all values from a resource tag before you can delete it.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteAsync (operations, tagName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-130">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="7c293-131">タグの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c293-131">The name of the tag.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c293-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c293-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-133">サブスクリプションからタグを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c293-133">Deletes a tag from the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c293-134">削除する前に、リソース タグからすべての値を削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c293-134">You must remove all values from a resource tag before you can delete it.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteValue">
      <MemberSignature Language="C#" Value="public static void DeleteValue (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteValue(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteValue(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteValue (operations As ITagsOperations, tagName As String, tagValue As String)" />
      <MemberSignature Language="F#" Value="static member DeleteValue : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteValue (operations, tagName, tagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-135">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="7c293-136">タグの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c293-136">The name of the tag.</span></span>
            </param>
        <param name="tagValue">
            <span data-ttu-id="7c293-137">削除するタグの値です。</span><span class="sxs-lookup"><span data-stu-id="7c293-137">The value of the tag to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-138">タグの値を削除します。</span><span class="sxs-lookup"><span data-stu-id="7c293-138">Deletes a tag value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteValueAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteValueAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteValueAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string tagName, string tagValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteValueAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteValueAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.DeleteValueAsync (operations, tagName, tagValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;DeleteValueAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-139">The operations group for this extension method.</span></span>
            </param>
        <param name="tagName">
            <span data-ttu-id="7c293-140">タグの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c293-140">The name of the tag.</span></span>
            </param>
        <param name="tagValue">
            <span data-ttu-id="7c293-141">削除するタグの値です。</span><span class="sxs-lookup"><span data-stu-id="7c293-141">The value of the tag to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c293-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c293-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-143">タグの値を削除します。</span><span class="sxs-lookup"><span data-stu-id="7c293-143">Deletes a tag value.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; List (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; List(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.ITagsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ITagsOperations) As IPage(Of TagDetails)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.ITagsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-144">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-145">名前とサブスクリプションで定義されているすべてのリソース タグの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c293-145">Gets the names and values of all resource tags that are defined in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-146">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c293-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c293-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-148">名前とサブスクリプションで定義されているすべてのリソース タグの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c293-148">Gets the names and values of all resource tags that are defined in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ITagsOperations, nextPageLink As String) As IPage(Of TagDetails)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-149">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7c293-150">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7c293-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-151">名前とサブスクリプションで定義されているすべてのリソース タグの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c293-151">Gets the names and values of all resource tags that are defined in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.ITagsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.ITagsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.ITagsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.TagsOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.TagDetails&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.ITagsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c293-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c293-152">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7c293-153">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7c293-153">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c293-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c293-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c293-155">名前とサブスクリプションで定義されているすべてのリソース タグの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c293-155">Gets the names and values of all resource tags that are defined in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>