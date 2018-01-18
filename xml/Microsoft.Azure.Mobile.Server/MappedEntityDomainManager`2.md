<Type Name="MappedEntityDomainManager&lt;TData,TModel&gt;" FullName="Microsoft.Azure.Mobile.Server.MappedEntityDomainManager&lt;TData,TModel&gt;">
  <TypeSignature Language="C#" Value="public abstract class MappedEntityDomainManager&lt;TData,TModel&gt; : Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;TData&gt; where TData : class, ITableData where TModel : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MappedEntityDomainManager`2&lt;class (class Microsoft.Azure.Mobile.Server.Tables.ITableData) TData, class TModel&gt; extends Microsoft.Azure.Mobile.Server.Tables.DomainManager`1&lt;!TData&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MappedEntityDomainManager(Of TData, TModel)&#xA;Inherits DomainManager(Of TData)" />
  <TypeSignature Language="F#" Value="type MappedEntityDomainManager&lt;'Data, 'Model (requires 'Data : null and 'Data :&gt; ITableData and 'Model : null)&gt; = class&#xA;    inherit DomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; ITableData)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TData">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.ITableData</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TModel">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;TData&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">TData</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TData"><span data-ttu-id="525a5-101">データ オブジェクト (DTO) を入力します。</span><span class="sxs-lookup"><span data-stu-id="525a5-101">The data object (DTO) type.</span></span></typeparam>
    <typeparam name="TModel"><span data-ttu-id="525a5-102">ドメインのデータ モデルの種類</span><span class="sxs-lookup"><span data-stu-id="525a5-102">The type of the domain data model</span></span></typeparam>
    <summary>
            <span data-ttu-id="525a5-103">提供、 <see cref="T:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1" /> Entity Framework を使用して、バックエンド ストアとして SQL を対象とする実装を通じて公開されるデータ オブジェクト (DTO) の間で 1:1 のマッピングがない、<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />と SQL によって管理されるドメイン モデル。</span><span class="sxs-lookup"><span data-stu-id="525a5-103">Provides an <see cref="T:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1" /> implementation targeting SQL as the backend store using Entity Framework where there is not a 1:1 mapping between the data object (DTO) exposed through a <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" /> and the domain model managed by SQL.</span></span>
            <span data-ttu-id="525a5-104">参照してください<see cref="T:Microsoft.Azure.Mobile.Server.EntityDomainManager`1" />の状況がデータ オブジェクト (DTO) と SQL によって管理されるドメイン モデルに 1 対 1 のリレーションシップが存在します。</span><span class="sxs-lookup"><span data-stu-id="525a5-104">See <see cref="T:Microsoft.Azure.Mobile.Server.EntityDomainManager`1" /> for situations where there is a 1:1 relationship between the Data Object (DTO) and the domain model managed by SQL.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="525a5-105"><see cref="T:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2" /> DTO と、ドメイン モデルにマップする AutoMapper を活用してでは、DTO からマップされる適切なマッピングと AutoMapper は既に初期化されていると見なされます =&gt;ドメイン モデルとドメイン モデルから =&gt; DTO です。</span><span class="sxs-lookup"><span data-stu-id="525a5-105">The <see cref="T:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2" /> leverages AutoMapper to map between the DTO and the domain model and it is assumed that AutoMapper has already been initialized with appropriate mappings that map from DTO =&gt; domain model and from domain model =&gt; DTO.</span></span> <span data-ttu-id="525a5-106">読み取り (GET、クエリ) と (PUT、POST、DELETE、修正プログラム) を関数に更新プログラムの両方について、双方向マッピングが必要です。</span><span class="sxs-lookup"><span data-stu-id="525a5-106">The bi-directional mapping is required for both reads (GET, QUERY) and updates (PUT, POST, DELETE, PATCH) to function.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MappedEntityDomainManager (System.Data.Entity.DbContext context, System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Data.Entity.DbContext context, class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.#ctor(System.Data.Entity.DbContext,System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (context As DbContext, request As HttpRequestMessage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.MappedEntityDomainManager&lt;'Data, 'Model (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData and 'Model : null)&gt; : System.Data.Entity.DbContext * System.Net.Http.HttpRequestMessage -&gt; Microsoft.Azure.Mobile.Server.MappedEntityDomainManager&lt;'Data, 'Model (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData and 'Model : null)&gt;" Usage="new Microsoft.Azure.Mobile.Server.MappedEntityDomainManager&lt;'Data, 'Model (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData and 'Model : null)&gt; (context, request)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="context" Type="System.Data.Entity.DbContext" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
      </Parameters>
      <Docs>
        <param name="context">
            <span data-ttu-id="525a5-107"><see cref="T:System.Data.Entity.DbContext" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="525a5-107">An instance of <see cref="T:System.Data.Entity.DbContext" /></span></span></param>
        <param name="request">
            <span data-ttu-id="525a5-108"><see cref="T:System.Net.Http.HttpRequestMessage" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="525a5-108">An instance of <see cref="T:System.Net.Http.HttpRequestMessage" /></span></span></param>
        <summary>
            <span data-ttu-id="525a5-109">新しいインスタンスを作成します。<see cref="T:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2" /></span><span class="sxs-lookup"><span data-stu-id="525a5-109">Creates a new instance of <see cref="T:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MappedEntityDomainManager (System.Data.Entity.DbContext context, System.Net.Http.HttpRequestMessage request, bool enableSoftDelete);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Data.Entity.DbContext context, class System.Net.Http.HttpRequestMessage request, bool enableSoftDelete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.#ctor(System.Data.Entity.DbContext,System.Net.Http.HttpRequestMessage,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (context As DbContext, request As HttpRequestMessage, enableSoftDelete As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.MappedEntityDomainManager&lt;'Data, 'Model (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData and 'Model : null)&gt; : System.Data.Entity.DbContext * System.Net.Http.HttpRequestMessage * bool -&gt; Microsoft.Azure.Mobile.Server.MappedEntityDomainManager&lt;'Data, 'Model (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData and 'Model : null)&gt;" Usage="new Microsoft.Azure.Mobile.Server.MappedEntityDomainManager&lt;'Data, 'Model (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData and 'Model : null)&gt; (context, request, enableSoftDelete)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="context" Type="System.Data.Entity.DbContext" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="enableSoftDelete" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="context">
            <span data-ttu-id="525a5-110"><see cref="T:System.Data.Entity.DbContext" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="525a5-110">An instance of <see cref="T:System.Data.Entity.DbContext" /></span></span></param>
        <param name="request">
            <span data-ttu-id="525a5-111"><see cref="T:System.Net.Http.HttpRequestMessage" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="525a5-111">An instance of <see cref="T:System.Net.Http.HttpRequestMessage" /></span></span></param>
        <param name="enableSoftDelete">
            <span data-ttu-id="525a5-112">行を削除または削除済みとしてマークがハードかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="525a5-112">Determines whether rows are hard deleted or marked as deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="525a5-113">新しいインスタンスを作成します。<see cref="T:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2" /></span><span class="sxs-lookup"><span data-stu-id="525a5-113">Creates a new instance of <see cref="T:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Data.Entity.DbContext Context { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.Entity.DbContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.Context" />
      <MemberSignature Language="VB.NET" Value="Public Property Context As DbContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Data.Entity.DbContext with get, set" Usage="Microsoft.Azure.Mobile.Server.MappedEntityDomainManager&lt;'Data, 'Model (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData and 'Model : null)&gt;.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Entity.DbContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteItemAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteItemAsync (params object[] keys);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteItemAsync(object[] keys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.DeleteItemAsync(System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function DeleteItemAsync (ParamArray keys As Object()) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteItemAsync : obj[] -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteItemAsync : obj[] -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="mappedEntityDomainManager.DeleteItemAsync keys" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2/&lt;DeleteItemAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keys" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="keys">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCompositeKey">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Azure.Mobile.Server.CompositeTableKey GetCompositeKey (string id);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.Mobile.Server.CompositeTableKey GetCompositeKey(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.GetCompositeKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function GetCompositeKey (id As String) As CompositeTableKey" />
      <MemberSignature Language="F#" Value="abstract member GetCompositeKey : string -&gt; Microsoft.Azure.Mobile.Server.CompositeTableKey&#xA;override this.GetCompositeKey : string -&gt; Microsoft.Azure.Mobile.Server.CompositeTableKey" Usage="mappedEntityDomainManager.GetCompositeKey id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed by caller.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.CompositeTableKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKey&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="protected virtual TKey GetKey&lt;TKey&gt; (string id);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance !!TKey GetKey&lt;TKey&gt;(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.GetKey``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function GetKey(Of TKey) (id As String) As TKey" />
      <MemberSignature Language="F#" Value="abstract member GetKey : string -&gt; 'Key&#xA;override this.GetKey : string -&gt; 'Key" Usage="mappedEntityDomainManager.GetKey id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TKey</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">To be added.</typeparam>
        <param name="id">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKey&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="protected virtual TKey GetKey&lt;TKey&gt; (string id, System.Globalization.CultureInfo culture);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance !!TKey GetKey&lt;TKey&gt;(string id, class System.Globalization.CultureInfo culture) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.GetKey``1(System.String,System.Globalization.CultureInfo)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function GetKey(Of TKey) (id As String, culture As CultureInfo) As TKey" />
      <MemberSignature Language="F#" Value="abstract member GetKey : string * System.Globalization.CultureInfo -&gt; 'Key&#xA;override this.GetKey : string * System.Globalization.CultureInfo -&gt; 'Key" Usage="mappedEntityDomainManager.GetKey (id, culture)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed by caller.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>TKey</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="culture" Type="System.Globalization.CultureInfo" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">To be added.</typeparam>
        <param name="id">To be added.</param>
        <param name="culture">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOriginalValue">
      <MemberSignature Language="C#" Value="protected virtual object GetOriginalValue (System.Data.Entity.Infrastructure.DbUpdateConcurrencyException conflict);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance object GetOriginalValue(class System.Data.Entity.Infrastructure.DbUpdateConcurrencyException conflict) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.GetOriginalValue(System.Data.Entity.Infrastructure.DbUpdateConcurrencyException)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function GetOriginalValue (conflict As DbUpdateConcurrencyException) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetOriginalValue : System.Data.Entity.Infrastructure.DbUpdateConcurrencyException -&gt; obj&#xA;override this.GetOriginalValue : System.Data.Entity.Infrastructure.DbUpdateConcurrencyException -&gt; obj" Usage="mappedEntityDomainManager.GetOriginalValue conflict" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1011:ConsiderPassingBaseTypesAsParameters", Justification="keeping the derived class is better from a usability point of view.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflict" Type="System.Data.Entity.Infrastructure.DbUpdateConcurrencyException" />
      </Parameters>
      <Docs>
        <param name="conflict"><span data-ttu-id="525a5-114"><see cref="T:System.Data.Entity.Infrastructure.DbUpdateConcurrencyException" />更新または置換操作でスローされます。</span><span class="sxs-lookup"><span data-stu-id="525a5-114">The <see cref="T:System.Data.Entity.Infrastructure.DbUpdateConcurrencyException" /> thrown by the update or replace operation.</span></span></param>
        <summary>
            <span data-ttu-id="525a5-115">エンティティの元の値を取得、更新または置換操作の結果の場合に、<see cref="T:System.Data.Entity.Infrastructure.DbUpdateConcurrencyException" />です。</span><span class="sxs-lookup"><span data-stu-id="525a5-115">Gets the original value of an entity in case an update or replace operation resulted in an <see cref="T:System.Data.Entity.Infrastructure.DbUpdateConcurrencyException" />.</span></span> <span data-ttu-id="525a5-116">例外から抽出された元の値は、データをマージして可能性のある、操作を再試行できるように、クライアントに返さを取得します。</span><span class="sxs-lookup"><span data-stu-id="525a5-116">The original value extracted from the exception will get returned to the client so that it can merge the data and possibly try the operation again.</span></span>
            </summary>
        <returns><span data-ttu-id="525a5-117">元の値または<c>null</c>いずれも利用できない場合。</span><span class="sxs-lookup"><span data-stu-id="525a5-117">The original value or <c>null</c> if none are available.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;TData&gt; InsertAsync (TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; InsertAsync(!TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function InsertAsync (data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="override this.InsertAsync : 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.InsertAsync data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2/&lt;InsertAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="data">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.SingleResult`1&lt;!TData&gt;&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function LookupAsync (id As String) As Task(Of SingleResult(Of TData))" />
      <MemberSignature Language="F#" Value="override this.LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;'Data&gt;&gt;" Usage="mappedEntityDomainManager.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupEntity">
      <MemberSignature Language="C#" Value="protected virtual System.Web.Http.SingleResult&lt;TData&gt; LookupEntity (System.Linq.Expressions.Expression&lt;Func&lt;TModel,bool&gt;&gt; filter);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Web.Http.SingleResult`1&lt;!TData&gt; LookupEntity(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!TModel, bool&gt;&gt; filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.LookupEntity(System.Linq.Expressions.Expression{System.Func{`1,System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function LookupEntity (filter As Expression(Of Func(Of TModel, Boolean))) As SingleResult(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member LookupEntity : System.Linq.Expressions.Expression&lt;Func&lt;'Model, bool&gt;&gt; -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.LookupEntity : System.Linq.Expressions.Expression&lt;Func&lt;'Model, bool&gt;&gt; -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.LookupEntity filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Required to pass an Expression.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Web.Http.SingleResult&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;TModel,System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="filter">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupEntity">
      <MemberSignature Language="C#" Value="protected virtual System.Web.Http.SingleResult&lt;TData&gt; LookupEntity (System.Linq.Expressions.Expression&lt;Func&lt;TModel,bool&gt;&gt; filter, bool includeDeleted);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Web.Http.SingleResult`1&lt;!TData&gt; LookupEntity(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!TModel, bool&gt;&gt; filter, bool includeDeleted) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.LookupEntity(System.Linq.Expressions.Expression{System.Func{`1,System.Boolean}},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function LookupEntity (filter As Expression(Of Func(Of TModel, Boolean)), includeDeleted As Boolean) As SingleResult(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member LookupEntity : System.Linq.Expressions.Expression&lt;Func&lt;'Model, bool&gt;&gt; * bool -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.LookupEntity : System.Linq.Expressions.Expression&lt;Func&lt;'Model, bool&gt;&gt; * bool -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.LookupEntity (filter, includeDeleted)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Required to pass an Expression.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Web.Http.SingleResult&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;TModel,System.Boolean&gt;&gt;" />
        <Parameter Name="includeDeleted" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="filter">To be added.</param>
        <param name="includeDeleted">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public override System.Linq.IQueryable&lt;TData&gt; Query ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Linq.IQueryable`1&lt;!TData&gt; Query() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.Query" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Query () As IQueryable(Of TData)" />
      <MemberSignature Language="F#" Value="override this.Query : unit -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.Query " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt; QueryAsync (System.Web.Http.OData.Query.ODataQueryOptions query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!TData&gt;&gt; QueryAsync(class System.Web.Http.OData.Query.ODataQueryOptions query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.QueryAsync(System.Web.Http.OData.Query.ODataQueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function QueryAsync (query As ODataQueryOptions) As Task(Of IEnumerable(Of TData))" />
      <MemberSignature Language="F#" Value="override this.QueryAsync : System.Web.Http.OData.Query.ODataQueryOptions -&gt; System.Threading.Tasks.Task&lt;seq&lt;'Data&gt;&gt;" Usage="mappedEntityDomainManager.QueryAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
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
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;TData&gt; ReplaceAsync (string id, TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; ReplaceAsync(string id, !TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.ReplaceAsync(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReplaceAsync (id As String, data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="override this.ReplaceAsync : string * 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.ReplaceAsync (id, data)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2/&lt;ReplaceAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="data">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetOriginalVersion">
      <MemberSignature Language="C#" Value="protected virtual void SetOriginalVersion (TModel model, byte[] version);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void SetOriginalVersion(!TModel model, unsigned int8[] version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.SetOriginalVersion(`1,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub SetOriginalVersion (model As TModel, version As Byte())" />
      <MemberSignature Language="F#" Value="abstract member SetOriginalVersion : 'Model * byte[] -&gt; unit&#xA;override this.SetOriginalVersion : 'Model * byte[] -&gt; unit" Usage="mappedEntityDomainManager.SetOriginalVersion (model, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="model" Type="TModel" />
        <Parameter Name="version" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="model"><span data-ttu-id="525a5-118">現在のエンティティ モデル オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="525a5-118">The current entity model object.</span></span></param>
        <param name="version"><span data-ttu-id="525a5-119">更新されるバージョンとして要求によって提供される元のバージョンまたは<c>null</c>バージョンが示されていない場合。</span><span class="sxs-lookup"><span data-stu-id="525a5-119">The original version provided by the request as being the version that is being updated; or <c>null</c> if no version was indicated.</span></span></param>
        <summary>
            <span data-ttu-id="525a5-120">オプティミスティック同時実行更新をサポートし、置換操作は、このメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="525a5-120">Override this method to support optimistic concurrent updates and replace operations.</span></span> <span data-ttu-id="525a5-121">オブジェクトが同時に更新されているかどうかを評価するために Entity Framework は編集されているオブジェクトの元のバージョンを調べることや、データベースに保持される現在のバージョンを比較する必要があります。</span><span class="sxs-lookup"><span data-stu-id="525a5-121">In order to evaluate whether an object has been updated concurrently, Entity Framework needs to know the original version of the object being edited and compare that to the current version maintained in the database.</span></span> <span data-ttu-id="525a5-122">これは、チェックを行うようにデータベースへの問い合わせができるように Entity Framework で元の値が呼ばれる必要があります。</span><span class="sxs-lookup"><span data-stu-id="525a5-122">This requires that the original value is known by Entity Framework so that it can ask the database to do the check.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="525a5-123">バージョンの管理に使用する列に"Version"が呼び出された場合に、元の値を設定するコードを以下に示します。</span><span class="sxs-lookup"><span data-stu-id="525a5-123">In case the column used to manage versioning is called "Version", the code to set the original value looks like this:</span></span>
            <code>
              this.context.Entry(model).OriginalValues["Version"] = version;
            </code></remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitChangesAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;int&gt; SubmitChangesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; SubmitChangesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.SubmitChangesAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function SubmitChangesAsync () As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="abstract member SubmitChangesAsync : unit -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.SubmitChangesAsync : unit -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mappedEntityDomainManager.SubmitChangesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="525a5-124">適切な生成、例外をログ出力中には、Entity Framework での変更内容を送信<see cref="T:System.Net.Http.HttpResponseMessage" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="525a5-124">Submits the change through Entity Framework while logging any exceptions and produce appropriate <see cref="T:System.Net.Http.HttpResponseMessage" /> instances.</span></span>
            </summary>
        <returns><span data-ttu-id="525a5-125">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="525a5-125">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;TData&gt; UndeleteAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UndeleteAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.UndeleteAsync(System.String,System.Web.Http.OData.Delta{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function UndeleteAsync (id As String, patch As Delta(Of TData)) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="override this.UndeleteAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.UndeleteAsync (id, patch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
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
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TData&gt; UpdateAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch, bool includeDeleted);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UpdateAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch, bool includeDeleted) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.UpdateAsync(System.String,System.Web.Http.OData.Delta{`0},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UpdateAsync (id As String, patch As Delta(Of TData), includeDeleted As Boolean) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="override this.UpdateAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; * bool -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.UpdateAsync (id, patch, includeDeleted)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
        <Parameter Name="includeDeleted" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="patch">To be added.</param>
        <param name="includeDeleted">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEntityAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;TData&gt; UpdateEntityAsync (System.Web.Http.OData.Delta&lt;TData&gt; patch, params object[] keys);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UpdateEntityAsync(class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch, object[] keys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.UpdateEntityAsync(System.Web.Http.OData.Delta{`0},System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function UpdateEntityAsync (patch As Delta(Of TData), ParamArray keys As Object()) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEntityAsync : System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; * obj[] -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.UpdateEntityAsync : System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; * obj[] -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.UpdateEntityAsync (patch, keys)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
        <Parameter Name="keys" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="patch">To be added.</param>
        <param name="keys">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEntityAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;TData&gt; UpdateEntityAsync (System.Web.Http.OData.Delta&lt;TData&gt; patch, bool includeDeleted, params object[] keys);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UpdateEntityAsync(class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch, bool includeDeleted, object[] keys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2.UpdateEntityAsync(System.Web.Http.OData.Delta{`0},System.Boolean,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function UpdateEntityAsync (patch As Delta(Of TData), includeDeleted As Boolean, ParamArray keys As Object()) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEntityAsync : System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; * bool * obj[] -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;&#xA;override this.UpdateEntityAsync : System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; * bool * obj[] -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="mappedEntityDomainManager.UpdateEntityAsync (patch, includeDeleted, keys)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.MappedEntityDomainManager`2/&lt;UpdateEntityAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
        <Parameter Name="includeDeleted" Type="System.Boolean" />
        <Parameter Name="keys" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="patch">To be added.</param>
        <param name="includeDeleted">To be added.</param>
        <param name="keys">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>