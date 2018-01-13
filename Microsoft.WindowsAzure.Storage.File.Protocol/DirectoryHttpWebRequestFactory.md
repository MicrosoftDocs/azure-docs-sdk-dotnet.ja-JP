<Type Name="DirectoryHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class DirectoryHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DirectoryHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class DirectoryHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type DirectoryHttpWebRequestFactory = class" />
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
            ファイル サービスのディレクトリでの操作用の web 要求を構築するためのファクトリ クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="request">Web 要求。</param>
        <param name="metadata">ユーザー定義のメタデータ。</param>
        <summary>
            ユーザー定義メタデータを要求に 1 つまたは複数の名前と値のペアとして追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request">Web 要求。</param>
        <param name="name">メタデータ名。</param>
        <param name="value">メタデータ値。</param>
        <summary>
            ユーザー定義メタデータを要求に 1 つの名前と値のペアとして追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ディレクトリの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            新しいディレクトリを作成する web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ディレクトリの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ディレクトリとその中のファイルをすべて削除する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ディレクトリの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            このディレクトリのユーザー定義メタデータを返す web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetMetadata (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ディレクトリの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="shareSnapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            このディレクトリのユーザー定義メタデータを返す web 要求を生成します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ディレクトリの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            このディレクトリのユーザー定義のメタデータとプロパティを返す web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.GetProperties (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ディレクトリの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="shareSnapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            このディレクトリのユーザー定義のメタデータとプロパティを返す web 要求を生成します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext listingContext, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext listingContext, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.List (uri, timeout, listingContext, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="listingContext">一覧作成操作のパラメーターのセット。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ディレクトリにすべてのファイルとサブディレクトリの一覧を返す web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext listingContext, Nullable&lt;DateTimeOffset&gt; shareSnapshot, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext listingContext, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext,System.Nullable{System.DateTimeOffset},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext * Nullable&lt;DateTimeOffset&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.List (uri, timeout, listingContext, shareSnapshot, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="listingContext">一覧作成操作のパラメーターのセット。</param>
        <param name="shareSnapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ディレクトリにすべてのファイルとサブディレクトリの一覧を返す web 要求を生成します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.DirectoryHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ディレクトリのユーザー定義メタデータを設定する web 要求を構築します。
            </summary>
        <returns>操作を実行するための web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>