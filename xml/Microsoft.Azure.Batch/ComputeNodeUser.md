<Type Name="ComputeNodeUser" FullName="Microsoft.Azure.Batch.ComputeNodeUser">
  <TypeSignature Language="C#" Value="public class ComputeNodeUser : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeUser extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ComputeNodeUser" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeUser&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type ComputeNodeUser = class&#xA;    interface ITransportObjectProvider&lt;ComputeNodeUser&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="21848-101">特定の Azure Batch のコンピューティング ノードのユーザー。</span><span class="sxs-lookup"><span data-stu-id="21848-101">A user for a specific Azure Batch compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics addOrUpdate = Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.AddUser, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(valuetype Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics addOrUpdate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNodeUser.Commit(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional addOrUpdate As ComputeNodeUserCommitSemantics = Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.AddUser, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNodeUser.Commit (addOrUpdate, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addOrUpdate" Type="Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="addOrUpdate"><span data-ttu-id="21848-102">実行するコミット操作の種類を選択します。</span><span class="sxs-lookup"><span data-stu-id="21848-102">Selects the type of commit operation to perform.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="21848-103">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</span><span class="sxs-lookup"><span data-stu-id="21848-103">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="21848-104">作成または計算ノード上のユーザー アカウントを更新する呼び出しをブロックしています。</span><span class="sxs-lookup"><span data-stu-id="21848-104">Blocking call to create or update a user account on the compute node.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics addOrUpdate = Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.AddUser, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(valuetype Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics addOrUpdate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNodeUser.CommitAsync(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNodeUser.CommitAsync (addOrUpdate, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addOrUpdate" Type="Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="addOrUpdate"><span data-ttu-id="21848-105">実行するコミット操作の種類を選択します。</span><span class="sxs-lookup"><span data-stu-id="21848-105">Selects the type of commit operation to perform.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="21848-106">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</span><span class="sxs-lookup"><span data-stu-id="21848-106">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="21848-107">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="21848-107">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="21848-108">作成または計算ノード上のユーザー アカウントを更新する非同期呼び出しを開始します。</span><span class="sxs-lookup"><span data-stu-id="21848-108">Begins an asynchronous call to create or update a user account on the compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="21848-109">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="21848-109">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21848-110">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" />です。</span><span class="sxs-lookup"><span data-stu-id="21848-110">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="21848-111">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="21848-111">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="21848-112">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="21848-112">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="21848-113">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="21848-113">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNodeUser.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNodeUser.Delete additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="21848-114">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</span><span class="sxs-lookup"><span data-stu-id="21848-114">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="21848-115">コンピューティング ノードから現在のユーザーを削除する呼び出しです。</span><span class="sxs-lookup"><span data-stu-id="21848-115">call to delete the current user from the compute node.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNodeUser.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNodeUser.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="21848-116">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</span><span class="sxs-lookup"><span data-stu-id="21848-116">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="21848-117">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="21848-117">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="21848-118">コンピューティング ノードから現在のユーザーを削除するための非同期呼び出しを開始します。</span><span class="sxs-lookup"><span data-stu-id="21848-118">Begins an asyncrhonous call to delete the current user from the compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="21848-119">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="21848-119">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public DateTime ExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.ExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21848-120">取得または、有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="21848-120">Gets or sets the expiry time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAdmin">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.IsAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAdmin As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAdmin : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.IsAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21848-121">取得またはユーザー アカウントの管理者の特権レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="21848-121">Gets or sets the administrative privilege level of the user account.</span></span> <span data-ttu-id="21848-122">コミット操作のため UpdateUser が指定されている場合、このプロパティの値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="21848-122">The value of this property is ignored when UpdateUser is specified for the commit operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21848-123">名前を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="21848-123">Gets or sets the name.</span></span> <span data-ttu-id="21848-124">コミット操作のため AddUser を指定すると、このプロパティの値が作成されるローカルの Windows アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="21848-124">If AddUser is specified for the commit operation, the value of this property is the name of the local Windows account created.</span></span> <span data-ttu-id="21848-125">コミット操作のため UpdateUser を指定すると、このプロパティの値は、ローカルの Windows アカウントの変更を選択します。</span><span class="sxs-lookup"><span data-stu-id="21848-125">If UpdateUser is specified for the commit operation, the value of this property selects the local Windows account to modify.</span></span> <span data-ttu-id="21848-126">このプロパティを変更しても、コンピューティング ノード上のローカル Windows アカウントの名前は変更されません。</span><span class="sxs-lookup"><span data-stu-id="21848-126">Changing this property does not rename the local Windows account on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21848-127">パスワードを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="21848-127">Gets or sets the password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPublicKey">
      <MemberSignature Language="C#" Value="public string SshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.SshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPublicKey : string with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.SshPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="21848-128">取得またはコンピューティング ノードにリモート ログインに使用できる SSH 公開キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="21848-128">Gets or sets the SSH public key that can be used for remote login to the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="21848-129">公開キーが開いている SSH エンコーディングと互換性があるし、base 64 エンコードします。</span><span class="sxs-lookup"><span data-stu-id="21848-129">The public key should be compatible with Open SSH encoding and should be base 64 encoded.</span></span> <span data-ttu-id="21848-130">このプロパティは、Linux ノードに対してのみ指定できます。</span><span class="sxs-lookup"><span data-stu-id="21848-130">This property can be specified only for Linux nodes.</span></span> <span data-ttu-id="21848-131">作成されたプールのこのプロパティが設定されている場合に、バッチ サービスがエラーを返します<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />または<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />Windows のコンピューティング ノードです。</span><span class="sxs-lookup"><span data-stu-id="21848-131">The Batch service will return an error if this property is set for pools created with <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> or <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> with Windows compute nodes.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>