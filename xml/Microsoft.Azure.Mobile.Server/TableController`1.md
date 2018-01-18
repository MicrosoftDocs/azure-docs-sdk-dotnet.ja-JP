<Type Name="TableController&lt;TData&gt;" FullName="Microsoft.Azure.Mobile.Server.TableController&lt;TData&gt;">
  <TypeSignature Language="C#" Value="public abstract class TableController&lt;TData&gt; : Microsoft.Azure.Mobile.Server.Tables.TableController where TData : class, ITableData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TableController`1&lt;class (class Microsoft.Azure.Mobile.Server.Tables.ITableData) TData&gt; extends Microsoft.Azure.Mobile.Server.Tables.TableController" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TableController`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TableController(Of TData)&#xA;Inherits TableController" />
  <TypeSignature Language="F#" Value="type TableController&lt;'Data (requires 'Data : null and 'Data :&gt; ITableData)&gt; = class&#xA;    inherit TableController" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TData">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.ITableData</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Tables.TableController</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TData"><span data-ttu-id="d7061-101">エンティティの型。</span><span class="sxs-lookup"><span data-stu-id="d7061-101">The type of the entity.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d7061-102">共通の<see cref="T:System.Web.Http.ApiController" />テーブル コント ローラーの抽象化します。</span><span class="sxs-lookup"><span data-stu-id="d7061-102">Provides a common <see cref="T:System.Web.Http.ApiController" /> abstraction for Table Controllers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TableController ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d7061-103"><see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d7061-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TableController (Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt; domainManager);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1&lt;!TData&gt; domainManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.#ctor(Microsoft.Azure.Mobile.Server.Tables.IDomainManager{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (domainManager As IDomainManager(Of TData))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TableController&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; : Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; Microsoft.Azure.Mobile.Server.TableController&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="new Microsoft.Azure.Mobile.Server.TableController&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; domainManager" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="domainManager" Type="Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt;" />
      </Parameters>
      <Docs>
        <param name="domainManager"><span data-ttu-id="d7061-104"><see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />このコント ローラーにします。</span><span class="sxs-lookup"><span data-stu-id="d7061-104">The <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> for this controller.</span></span></param>
        <summary>
            <span data-ttu-id="d7061-105">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />クラスに、指定された<paramref name="domainManager" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" /> class with a given <paramref name="domainManager" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task DeleteAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.DeleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function DeleteAsync (id As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="tableController.DeleteAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed in the response path.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.TableController`1/&lt;DeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-106">バックエンド ストアからエンティティを削除するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-106">Provides a helper method for deleting an entity from a backend store.</span></span> <span data-ttu-id="d7061-107">によってスローされた例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-107">It deals with any exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-108">A<see cref="T:System.Threading.Tasks.Task`1" />によって実行される delete 操作を表す、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-108">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the delete operation executed by the the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainManager">
      <MemberSignature Language="C#" Value="protected Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt; DomainManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1&lt;!TData&gt; DomainManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TableController`1.DomainManager" />
      <MemberSignature Language="VB.NET" Value="Protected Property DomainManager As IDomainManager(Of TData)" />
      <MemberSignature Language="F#" Value="member this.DomainManager : Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.TableController&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;.DomainManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7061-109">取得または設定、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />バックエンド ストアにアクセスするために使用します。</span><span class="sxs-lookup"><span data-stu-id="d7061-109">Gets or sets the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> to be used for accessing the backend store.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="protected override void Initialize (System.Web.Http.Controllers.HttpControllerContext controllerContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Initialize(class System.Web.Http.Controllers.HttpControllerContext controllerContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.Initialize(System.Web.Http.Controllers.HttpControllerContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Initialize (controllerContext As HttpControllerContext)" />
      <MemberSignature Language="F#" Value="override this.Initialize : System.Web.Http.Controllers.HttpControllerContext -&gt; unit" Usage="tableController.Initialize controllerContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="controllerContext" Type="System.Web.Http.Controllers.HttpControllerContext" />
      </Parameters>
      <Docs>
        <param name="controllerContext">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;TData&gt; InsertAsync (TData item);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; InsertAsync(!TData item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function InsertAsync (item As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.InsertAsync : 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="tableController.InsertAsync item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed in the response path.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.TableController`1/&lt;InsertAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="TData" />
      </Parameters>
      <Docs>
        <param name="item">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-110">バックエンド ストアにエンティティを挿入するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-110">Provides a helper method for inserting an entity into a backend store.</span></span> <span data-ttu-id="d7061-111">モデル検証エラーだけでなくによってスローされる例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-111">It deals with any model validation errors as well as exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-112">A<see cref="T:System.Threading.Tasks.Task`1" />によって実行される挿入操作を表す、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-112">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the insert operation executed by the the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lookup">
      <MemberSignature Language="C#" Value="protected virtual System.Web.Http.SingleResult&lt;TData&gt; Lookup (string id);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Web.Http.SingleResult`1&lt;!TData&gt; Lookup(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.Lookup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function Lookup (id As String) As SingleResult(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Lookup : string -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.Lookup : string -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="tableController.Lookup id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Caller disposes response.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Web.Http.SingleResult&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-113">バックエンド ストア内のエンティティを検索するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-113">Provides a helper method for looking up an entity in a backend store.</span></span> <span data-ttu-id="d7061-114">によってスローされた例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-114">It deals with any exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-115"><see cref="T:System.Web.Http.SingleResult`1" />によって返される、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-115">An <see cref="T:System.Web.Http.SingleResult`1" /> returned by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.SingleResult`1&lt;!TData&gt;&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function LookupAsync (id As String) As Task(Of SingleResult(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;'Data&gt;&gt;&#xA;override this.LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;'Data&gt;&gt;" Usage="tableController.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Caller disposes response.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.TableController`1/&lt;LookupAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-116">バックエンド ストア内のエンティティを検索するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-116">Provides a helper method for looking up an entity in a backend store.</span></span> <span data-ttu-id="d7061-117">によってスローされた例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-117">It deals with any exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-118"><see cref="T:System.Web.Http.SingleResult`1" />によって返される、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-118">An <see cref="T:System.Web.Http.SingleResult`1" /> returned by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="protected virtual System.Linq.IQueryable&lt;TData&gt; Query ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!TData&gt; Query() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.Query" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function Query () As IQueryable(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Query : unit -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.Query : unit -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="tableController.Query " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Caller disposes response.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d7061-119">バックエンド ストアのクエリを実行するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-119">Provides a helper method for querying a backend store.</span></span> <span data-ttu-id="d7061-120">によってスローされた例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-120">It deals with any exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-121"><see cref="T:System.Linq.IQueryable`1" />によって返される、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-121">An <see cref="T:System.Linq.IQueryable`1" /> returned by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt; QueryAsync (System.Web.Http.OData.Query.ODataQueryOptions query);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!TData&gt;&gt; QueryAsync(class System.Web.Http.OData.Query.ODataQueryOptions query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.QueryAsync(System.Web.Http.OData.Query.ODataQueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function QueryAsync (query As ODataQueryOptions) As Task(Of IEnumerable(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member QueryAsync : System.Web.Http.OData.Query.ODataQueryOptions -&gt; System.Threading.Tasks.Task&lt;seq&lt;'Data&gt;&gt;&#xA;override this.QueryAsync : System.Web.Http.OData.Query.ODataQueryOptions -&gt; System.Threading.Tasks.Task&lt;seq&lt;'Data&gt;&gt;" Usage="tableController.QueryAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.Web.Http.OData.Query.ODataQueryOptions" />
      </Parameters>
      <Docs>
        <param name="query">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-122">バックエンド ストアのクエリを実行するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-122">Provides a helper method for querying a backend store.</span></span> <span data-ttu-id="d7061-123">によってスローされた例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-123">It deals with any exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-124"><see cref="T:System.Linq.IQueryable`1" />によって返される、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-124">An <see cref="T:System.Linq.IQueryable`1" /> returned by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;TData&gt; ReplaceAsync (string id, TData item);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; ReplaceAsync(string id, !TData item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.ReplaceAsync(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function ReplaceAsync (id As String, item As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAsync : string * 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.ReplaceAsync : string * 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="tableController.ReplaceAsync (id, item)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed in the response path.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.TableController`1/&lt;ReplaceAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="item" Type="TData" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="item">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-125">バックエンド ストア内のエンティティを置換するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-125">Provides a helper method for replacing an entity in a backend store.</span></span> <span data-ttu-id="d7061-126">モデル検証エラーだけでなくによってスローされる例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-126">It deals with any model validation errors as well as exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-127">A<see cref="T:System.Threading.Tasks.Task`1" />によって実行される置換操作を表す、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-127">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the replace operation executed by the the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;TData&gt; UndeleteAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UndeleteAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.UndeleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function UndeleteAsync (id As String) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : string -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.UndeleteAsync : string -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="tableController.UndeleteAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-128">バックエンド ストア内のエンティティを削除するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-128">Provides a helper method for undeleting an entity in a backend store.</span></span> <span data-ttu-id="d7061-129">モデル検証エラーだけでなくによってスローされる例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-129">It deals with any model validation errors as well as exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-130">A<see cref="T:System.Threading.Tasks.Task`1" />によって実行される update 操作を表す、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-130">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the update operation executed by the the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;TData&gt; UndeleteAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UndeleteAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.UndeleteAsync(System.String,System.Web.Http.OData.Delta{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function UndeleteAsync (id As String, patch As Delta(Of TData)) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.UndeleteAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="tableController.UndeleteAsync (id, patch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed in the response path.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="patch">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-131">バックエンド ストア内のエンティティを削除するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-131">Provides a helper method for undeleting an entity in a backend store.</span></span> <span data-ttu-id="d7061-132">モデル検証エラーだけでなくによってスローされる例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-132">It deals with any model validation errors as well as exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-133">A<see cref="T:System.Threading.Tasks.Task`1" />によって実行される削除の取り消し操作を表す、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-133">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the undelete operation executed by the the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;TData&gt; UpdateAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UpdateAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TableController`1.UpdateAsync(System.String,System.Web.Http.OData.Delta{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function UpdateAsync (id As String, patch As Delta(Of TData)) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.UpdateAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="tableController.UpdateAsync (id, patch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="patch">To be added.</param>
        <summary>
            <span data-ttu-id="d7061-134">バックエンド ストア内のエンティティを更新するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="d7061-134">Provides a helper method for updating an entity in a backend store.</span></span> <span data-ttu-id="d7061-135">モデル検証エラーだけでなくによってスローされる例外を処理、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />し、適切な HTTP 応答にマッピングします。</span><span class="sxs-lookup"><span data-stu-id="d7061-135">It deals with any model validation errors as well as exceptions thrown by the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> and maps them into appropriate HTTP responses.</span></span>
            </summary>
        <returns><span data-ttu-id="d7061-136">A<see cref="T:System.Threading.Tasks.Task`1" />によって実行される update 操作を表す、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />です。</span><span class="sxs-lookup"><span data-stu-id="d7061-136">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the update operation executed by the the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>