<Type Name="TableHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class TableHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class TableHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type TableHttpWebRequestFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d4099-101">テーブル サービスでテーブルを管理する web 要求を構築するためのファクトリ クラスです。</span><span class="sxs-lookup"><span data-stu-id="d4099-101">A factory class for constructing a web request to manage tables in the Table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.GetAcl(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.GetAcl (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d4099-102">A<see cref="T:System.Uri" />テーブルの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="d4099-102">A <see cref="T:System.Uri" /> specifying the absolute URI for the table.</span></span></param>
        <param name="builder"><span data-ttu-id="d4099-103">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-103">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d4099-104">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="d4099-104">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d4099-105"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-105">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d4099-106">テーブルの ACL を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="d4099-106">Constructs a web request to return the ACL for a table.</span></span>
            </summary>
        <returns><span data-ttu-id="d4099-107"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-107">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.GetAcl(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.GetAcl (uri, builder, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d4099-108">A<see cref="T:System.Uri" />テーブルの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="d4099-108">A <see cref="T:System.Uri" /> specifying the absolute URI for the table.</span></span></param>
        <param name="builder"><span data-ttu-id="d4099-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d4099-110">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="d4099-110">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d4099-111">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="d4099-111">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d4099-112"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-112">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d4099-113">テーブルの ACL を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="d4099-113">Constructs a web request to return the ACL for a table.</span></span>
            </summary>
        <returns><span data-ttu-id="d4099-114"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-114">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d4099-115">A<see cref="T:System.Uri" />テーブル サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="d4099-115">A <see cref="T:System.Uri" /> specifying the Table service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="d4099-116">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-116">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d4099-117">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="d4099-117">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d4099-118"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-118">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d4099-119">テーブル サービスのプロパティを取得する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="d4099-119">Creates a web request to get the properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d4099-120"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-120">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d4099-121">A<see cref="T:System.Uri" />テーブル サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="d4099-121">A <see cref="T:System.Uri" /> specifying the Table service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="d4099-122">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-122">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d4099-123">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="d4099-123">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d4099-124"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-124">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d4099-125">テーブル サービスの統計情報を取得する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="d4099-125">Creates a web request to get the stats of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d4099-126"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-126">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.SetAcl(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.SetAcl (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d4099-127">A<see cref="T:System.Uri" />テーブルの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="d4099-127">A <see cref="T:System.Uri" /> specifying the absolute URI for the table.</span></span></param>
        <param name="builder"><span data-ttu-id="d4099-128">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-128">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d4099-129">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="d4099-129">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d4099-130"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-130">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d4099-131">テーブルの ACL を設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="d4099-131">Constructs a web request to set the ACL for a table.</span></span>
            </summary>
        <returns><span data-ttu-id="d4099-132"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-132">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.SetAcl(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.SetAcl (uri, builder, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d4099-133">A<see cref="T:System.Uri" />テーブルの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="d4099-133">A <see cref="T:System.Uri" /> specifying the absolute URI for the table.</span></span></param>
        <param name="builder"><span data-ttu-id="d4099-134">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-134">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d4099-135">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="d4099-135">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="d4099-136">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="d4099-136">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d4099-137"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-137">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d4099-138">テーブルの ACL を設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="d4099-138">Constructs a web request to set the ACL for a table.</span></span>
            </summary>
        <returns><span data-ttu-id="d4099-139"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-139">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="d4099-140">A<see cref="T:System.Uri" />テーブル サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="d4099-140">A <see cref="T:System.Uri" /> specifying the Table service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="d4099-141">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-141">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="d4099-142">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="d4099-142">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d4099-143"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-143">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d4099-144">テーブル サービスのプロパティを設定する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="d4099-144">Creates a web request to set the properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="d4099-145"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-145">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Table.Protocol.TableHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d4099-146">A<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />を書式設定し、ストリームに書き込むサービス プロパティを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-146">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object containing the service properties to format and write to the stream.</span></span></param>
        <param name="outputStream"><span data-ttu-id="d4099-147"><see cref="T:System.IO.Stream" />書式設定されたプロパティが書き込まれるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4099-147">The <see cref="T:System.IO.Stream" /> object to which the formatted properties are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="d4099-148">テーブル サービス プロパティを XML 形式で、ストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="d4099-148">Writes Table service properties to a stream, formatted in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>