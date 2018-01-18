<Type Name="ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt;">
  <TypeSignature Language="C#" Value="public abstract class ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;InnerModelT,ParentImplT,IParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;FluentModelT&gt; where FluentModelT : class, IExternalChildResource&lt;FluentModelT,IParentT&gt; where ParentImplT : IParentT" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ExternalChildResource`4&lt;class (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;!FluentModelT, !IParentT&gt;) FluentModelT, InnerModelT, IParentT, (!IParentT) ParentImplT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3&lt;!InnerModelT, !ParentImplT, !IParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;!FluentModelT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ExternalChildResource(Of FluentModelT, InnerModelT, IParentT, ParentImplT)&#xA;Inherits ChildResource(Of InnerModelT, ParentImplT, IParentT)&#xA;Implements IRefreshable(Of FluentModelT)" />
  <TypeSignature Language="F#" Value="type ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; = class&#xA;    inherit ChildResource&lt;'InnerModelT, #'IParentT, 'IParentT&gt;&#xA;    interface IRefreshable&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentModelT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;FluentModelT,IParentT&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="InnerModelT" />
    <TypeParameter Name="IParentT" />
    <TypeParameter Name="ParentImplT">
      <Constraints>
        <BaseTypeName>IParentT</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;InnerModelT,ParentImplT,IParentT&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="InnerT">InnerModelT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="ParentImplT">ParentImplT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IParentT">IParentT</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;FluentModelT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="FluentModelT"><span data-ttu-id="7ab90-101">外部の子リソース fluent インターフェイス</span><span class="sxs-lookup"><span data-stu-id="7ab90-101">the external child resource fluent interface</span></span></typeparam>
    <typeparam name="InnerModelT"><span data-ttu-id="7ab90-102">Azure の内部リソース クラス型の子リソースを表す</span><span class="sxs-lookup"><span data-stu-id="7ab90-102">Azure inner resource class type representing the child resource</span></span></typeparam>
    <typeparam name="IParentT"><span data-ttu-id="7ab90-103">親 fluent インターフェイス</span><span class="sxs-lookup"><span data-stu-id="7ab90-103">parent fluent interface</span></span></typeparam>
    <typeparam name="ParentImplT"><span data-ttu-id="7ab90-104">親リソースの実装の種類</span><span class="sxs-lookup"><span data-stu-id="7ab90-104">parent resource implementation type</span></span></typeparam>
    <summary>
            <span data-ttu-id="7ab90-105">子の外部化されたリソースの抽象実装。</span><span class="sxs-lookup"><span data-stu-id="7ab90-105">Externalized child resource abstract implementation.</span></span>
            <span data-ttu-id="7ab90-106">次の条件を満たす必要のある外部の子リソースの対象となる: するには</span><span class="sxs-lookup"><span data-stu-id="7ab90-106">In order to be eligible for an external child resource following criteria must be satisfied:</span></span>
            1. <span data-ttu-id="7ab90-107">これは、親リソースに関連付けられては常にあり、親の親、子のリソースを削除する場合などが自動的に削除することがなく存在がありません。</span><span class="sxs-lookup"><span data-stu-id="7ab90-107">It's is always associated with a parent resource and has no existence without parent i.e. if you delete parent then child resource will be deleted automatically.</span></span>
            2. <span data-ttu-id="7ab90-108">親は、子リソースのコレクション (つまりとしてインライン コレクション プロパティ) を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="7ab90-108">Parent may or may not contain collection of child resources (i.e. as inline collection property).</span></span>
            <span data-ttu-id="7ab90-109">Id はおよび作成、更新、フェッチ、削除子リソースの親 i.e.CRUD とは無関係では、親 (内部使用のみ) では、CRUD は不要</span><span class="sxs-lookup"><span data-stu-id="7ab90-109">It's has an ID and can be created, updated, fetched and deleted independent of the parent i.e.CRUD on child resource does not require CRUD on the parent (Internal use only)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExternalChildResource (string name, ParentImplT parent, InnerModelT innerObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, !ParentImplT parent, !InnerModelT innerObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.#ctor(System.String,`3,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, parent As ParentImplT, innerObject As InnerModelT)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; : string * 'ParentImplT * 'InnerModelT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; (name, parent, innerObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parent" Type="ParentImplT" />
        <Parameter Name="innerObject" Type="InnerModelT" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7ab90-110">この外部の子リソースの名前</span><span class="sxs-lookup"><span data-stu-id="7ab90-110">the name of this external child resource</span></span></param>
        <param name="parent"><span data-ttu-id="7ab90-111">この外部の子リソースの親への参照します。</span><span class="sxs-lookup"><span data-stu-id="7ab90-111">reference to the parent of this external child resource</span></span></param>
        <param name="innerObject"><span data-ttu-id="7ab90-112">この外部の子リソースを表す内部オブジェクトへの参照します。</span><span class="sxs-lookup"><span data-stu-id="7ab90-112">reference to the inner object representing this external child resource</span></span></param>
        <summary>
            <span data-ttu-id="7ab90-113">外部の子リソースのメモリ内のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="7ab90-113">Creates an instance of external child resource in-memory.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChildResourceKey">
      <MemberSignature Language="C#" Value="public virtual string ChildResourceKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ChildResourceKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.ChildResourceKey" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ChildResourceKey As String" />
      <MemberSignature Language="F#" Value="member this.ChildResourceKey : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;.ChildResourceKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;FluentModelT&gt; CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.CreateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="7ab90-114">この外部の子リソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="7ab90-114">Creates this external child resource.</span></span>
            </summary>
        <returns><span data-ttu-id="7ab90-115">作成アクションを追跡するタスク</span><span class="sxs-lookup"><span data-stu-id="7ab90-115">the task to track the create action</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="externalChildResource.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="7ab90-116">この外部の子リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ab90-116">Deletes this external child resource.</span></span>
            </summary>
        <returns><span data-ttu-id="7ab90-117">削除操作を追跡するタスク</span><span class="sxs-lookup"><span data-stu-id="7ab90-117">the task to track the delete action</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInnerAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;InnerModelT&gt; GetInnerAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!InnerModelT&gt; GetInnerAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.GetInnerAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetInnerAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'InnerModelT&gt;" Usage="externalChildResource.GetInnerAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;InnerModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public override string Name ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string Name() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.Name" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Name () As String" />
      <MemberSignature Language="F#" Value="override this.Name : unit -&gt; string" Usage="externalChildResource.Name " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingOperation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation PendingOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation PendingOperation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.PendingOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingOperation As PendingOperation" />
      <MemberSignature Language="F#" Value="member this.PendingOperation : Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;.PendingOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="7ab90-118">この子リソースと状態のインメモリ状態では、保留中の子リソースに対してアクションを表します。</span><span class="sxs-lookup"><span data-stu-id="7ab90-118">the in-memory state of this child resource and state represents any pending action on the child resource.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public virtual FluentModelT Refresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !FluentModelT Refresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.Refresh" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Refresh () As FluentModelT" />
      <MemberSignature Language="F#" Value="abstract member Refresh : unit -&gt; 'FluentModelT&#xA;override this.Refresh : unit -&gt; 'FluentModelT" Usage="externalChildResource.Refresh " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.Refresh</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentModelT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;FluentModelT&gt; RefreshAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; RefreshAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.RefreshAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;&#xA;override this.RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.RefreshAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.RefreshAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4/&lt;RefreshAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;FluentModelT&gt; UpdateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; UpdateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.UpdateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.UpdateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="7ab90-119">この外部の子リソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ab90-119">Updates this external child resource.</span></span>
            </summary>
        <returns><span data-ttu-id="7ab90-120">[更新] 操作を追跡するタスク</span><span class="sxs-lookup"><span data-stu-id="7ab90-120">the task to track the update action</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>