<Type Name="TableHttpRequestMessageExtensions" FullName="System.Net.Http.TableHttpRequestMessageExtensions">
  <TypeSignature Language="C#" Value="public static class TableHttpRequestMessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableHttpRequestMessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Net.Http.TableHttpRequestMessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableHttpRequestMessageExtensions" />
  <TypeSignature Language="F#" Value="type TableHttpRequestMessageExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e3344-101">拡張メソッドを<see cref="T:System.Net.Http.HttpRequestMessage" />テーブルに関連する機能を提供するクラス<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />です。</span><span class="sxs-lookup"><span data-stu-id="e3344-101">Extension methods for the <see cref="T:System.Net.Http.HttpRequestMessage" /> class providing functionality related to table <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AreDeletedRowsRequested">
      <MemberSignature Language="C#" Value="public static bool AreDeletedRowsRequested (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool AreDeletedRowsRequested(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.AreDeletedRowsRequested(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AreDeletedRowsRequested (request As HttpRequestMessage) As Boolean" />
      <MemberSignature Language="F#" Value="static member AreDeletedRowsRequested : System.Net.Http.HttpRequestMessage -&gt; bool" Usage="System.Net.Http.TableHttpRequestMessageExtensions.AreDeletedRowsRequested request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="e3344-102"><see cref="T:System.Net.Http.HttpRequestMessage" />要求</span><span class="sxs-lookup"><span data-stu-id="e3344-102">The <see cref="T:System.Net.Http.HttpRequestMessage" />request</span></span></param>
        <summary>
            <span data-ttu-id="e3344-103">クライアントによって要求された行を削除するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="e3344-103">Determines whether deleted rows were requested by the client.</span></span>
            </summary>
        <returns><span data-ttu-id="e3344-104">True の場合は、削除された行は、要求された、それ以外の場合は False。</span><span class="sxs-lookup"><span data-stu-id="e3344-104">True if the deleted rows are requested, otherwise False.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionFromIfMatch">
      <MemberSignature Language="C#" Value="public static byte[] GetVersionFromIfMatch (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig unsigned int8[] GetVersionFromIfMatch(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.GetVersionFromIfMatch(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVersionFromIfMatch (request As HttpRequestMessage) As Byte()" />
      <MemberSignature Language="F#" Value="static member GetVersionFromIfMatch : System.Net.Http.HttpRequestMessage -&gt; byte[]" Usage="System.Net.Http.TableHttpRequestMessageExtensions.GetVersionFromIfMatch request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope", Justification="Response is disposed by caller.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"></param>
        <summary>
            <span data-ttu-id="e3344-105">HTTP からテーブルの項目のバージョンを取得<c>IfMatch</c>ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="e3344-105">Gets the version of a table item from the HTTP <c>IfMatch</c> header.</span></span> <span data-ttu-id="e3344-106">場合、 <c>IfMatch</c>に無効な値が含まれています、<see cref="T:System.Web.Http.HttpResponseException" />がスローされます、<see cref="T:System.Net.Http.HttpResponseMessage" />ステータス コードで<see cref="F:System.Net.HttpStatusCode.BadRequest" />です。</span><span class="sxs-lookup"><span data-stu-id="e3344-106">If the <c>IfMatch</c> contains an invalid value then an <see cref="T:System.Web.Http.HttpResponseException" /> is thrown containing an <see cref="T:System.Net.Http.HttpResponseMessage" /> with status code <see cref="F:System.Net.HttpStatusCode.BadRequest" />.</span></span>
            </summary>
        <returns><span data-ttu-id="e3344-107">バージョンを表す有効なバージョンのバイト配列または<c>null</c> [なし] が存在していた場合。</span><span class="sxs-lookup"><span data-stu-id="e3344-107">A valid version byte array representing the version, or <c>null</c> if none were present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSelectedProperties">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; SetSelectedProperties (this System.Net.Http.HttpRequestMessage request, Type data, out bool isModified);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; SetSelectedProperties(class System.Net.Http.HttpRequestMessage request, class System.Type data, [out] bool&amp; isModified) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties(System.Net.Http.HttpRequestMessage,System.Type,System.Boolean@)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetSelectedProperties (request As HttpRequestMessage, data As Type, ByRef isModified As Boolean) As IList(Of String)" />
      <MemberSignature Language="F#" Value="static member SetSelectedProperties : System.Net.Http.HttpRequestMessage * Type *  -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties (request, data, isModified)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="It's ok to have an out parameter here.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="data" Type="System.Type" />
        <Parameter Name="isModified" Type="System.Boolean&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="e3344-108"><see cref="T:System.Net.Http.HttpRequestMessage" />要求</span><span class="sxs-lookup"><span data-stu-id="e3344-108">The <see cref="T:System.Net.Http.HttpRequestMessage" />request</span></span></param>
        <param name="data"><span data-ttu-id="e3344-109">データ モデルの型。</span><span class="sxs-lookup"><span data-stu-id="e3344-109">The type of the data model.</span></span></param>
        <param name="isModified"><span data-ttu-id="e3344-110">元の要求 URI の $select 句が操作されているかどうかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="e3344-110">Indicates whether the original Request URI $select clause has been manipulated or not.</span></span></param>
        <summary>
            <span data-ttu-id="e3344-111">実装する型の OData の $select クエリ オプションで含めるプロパティのセットを決定する、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="e3344-111">Determines the set of properties to include in the OData $select query option for types implementing the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> interface.</span></span> <span data-ttu-id="e3344-112">この関数は、選択したプロパティのセットを決定し、必要に応じて、要求の URI をそれに応じて更新します。</span><span class="sxs-lookup"><span data-stu-id="e3344-112">This function determines the set of selected properties and updates the request URI accordingly, if necessary.</span></span>
            </summary>
        <returns><span data-ttu-id="e3344-113">選択されているプロパティのセットを実装する型の場合それ以外の場合は null。</span><span class="sxs-lookup"><span data-stu-id="e3344-113">In the case of a type implementing, the set of properties selected; otherwise null.</span></span></returns>
        <remarks><span data-ttu-id="e3344-114">クエリは実際には検証されません - この手順ではこれはの一部として実行、<see cref="T:System.Web.Http.QueryableAttribute" />検証します。</span><span class="sxs-lookup"><span data-stu-id="e3344-114">The query is not actually validated in this step -- this happens as part of the <see cref="T:System.Web.Http.QueryableAttribute" /> validation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSelectedProperties">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; SetSelectedProperties (this System.Net.Http.HttpRequestMessage request, Type data, System.Collections.Generic.IDictionary&lt;string,string&gt; systemPropertyMap, out bool isModified);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; SetSelectedProperties(class System.Net.Http.HttpRequestMessage request, class System.Type data, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; systemPropertyMap, [out] bool&amp; isModified) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties(System.Net.Http.HttpRequestMessage,System.Type,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean@)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetSelectedProperties (request As HttpRequestMessage, data As Type, systemPropertyMap As IDictionary(Of String, String), ByRef isModified As Boolean) As IList(Of String)" />
      <MemberSignature Language="F#" Value="static member SetSelectedProperties : System.Net.Http.HttpRequestMessage * Type * System.Collections.Generic.IDictionary&lt;string, string&gt; *  -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="System.Net.Http.TableHttpRequestMessageExtensions.SetSelectedProperties (request, data, systemPropertyMap, isModified)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="It's ok to have an out parameter here.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="data" Type="System.Type" />
        <Parameter Name="systemPropertyMap" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="isModified" Type="System.Boolean&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="e3344-115"><see cref="T:System.Net.Http.HttpRequestMessage" />要求</span><span class="sxs-lookup"><span data-stu-id="e3344-115">The <see cref="T:System.Net.Http.HttpRequestMessage" />request</span></span></param>
        <param name="data"><span data-ttu-id="e3344-116">データ モデルの型。</span><span class="sxs-lookup"><span data-stu-id="e3344-116">The type of the data model.</span></span></param>
        <param name="systemPropertyMap"><span data-ttu-id="e3344-117">システムのプロパティの代替名を指定する省略可能なマップします。</span><span class="sxs-lookup"><span data-stu-id="e3344-117">Optional map specifying replacement names for system properties.</span></span></param>
        <param name="isModified"><span data-ttu-id="e3344-118">元の要求 URI の $select 句が操作されているかどうかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="e3344-118">Indicates whether the original Request URI $select clause has been manipulated or not.</span></span></param>
        <summary>
            <span data-ttu-id="e3344-119">実装する型の OData の $select クエリ オプションで含めるプロパティのセットを決定する、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="e3344-119">Determines the set of properties to include in the OData $select query option for types implementing the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> interface.</span></span> <span data-ttu-id="e3344-120">この関数は、選択したプロパティの組み合わせのセットを決定し、必要に応じて、要求の URI をそれに応じて更新します。</span><span class="sxs-lookup"><span data-stu-id="e3344-120">This function determines the combined set of selected properties and updates the request URI accordingly, if necessary.</span></span>
            </summary>
        <returns><span data-ttu-id="e3344-121">選択されているプロパティのセットを実装する型の場合それ以外の場合は null。</span><span class="sxs-lookup"><span data-stu-id="e3344-121">In the case of a type implementing, the set of properties selected; otherwise null.</span></span></returns>
        <remarks><span data-ttu-id="e3344-122">クエリは実際には検証されません - この手順ではこれはの一部として実行、<see cref="T:System.Web.Http.QueryableAttribute" />検証します。</span><span class="sxs-lookup"><span data-stu-id="e3344-122">The query is not actually validated in this step -- this happens as part of the <see cref="T:System.Web.Http.QueryableAttribute" /> validation.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>