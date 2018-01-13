<Type Name="FileHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class FileHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class FileHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type FileHttpWebRequestFactory = class" />
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
            ファイル サービス内のファイルに対する操作の web 要求を構築するためのファクトリ クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbortCopy">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AbortCopy (Uri uri, Nullable&lt;int&gt; timeout, string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AbortCopy(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AbortCopy(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AbortCopy : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AbortCopy (uri, timeout, copyId, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />ファイルへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="copyId">中止するコピー操作の ID 文字列です。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 リース条件のみが、この操作でサポートされます。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            コピー操作を中止する web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.CopyFrom (uri, timeout, source, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />出力先ファイルの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="source">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、変換先ファイルに満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob またはファイルから別のファイルにコピーする web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileProperties properties, long fileSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileProperties properties, int64 fileSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileProperties,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileProperties * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Create (uri, timeout, properties, fileSize, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileProperties" />
        <Parameter Name="fileSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="properties">ファイルに対して設定するプロパティ。</param>
        <param name="fileSize">ファイルのサイズ。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            新しいファイルを作成する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルを削除する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルのコンテンツ、プロパティ、およびメタデータを取得する web 要求を構築します。
            </summary>
        <returns>操作を実行するための web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="shareSnapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルのコンテンツ、プロパティ、およびメタデータを取得する web 要求を構築します。
            </summary>
        <returns>操作を実行するための web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, offset, count, rangeContentMD5, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="offset">コンテンツを返すを開始するバイト オフセットです。</param>
        <param name="count">戻り値、またはファイルの末尾まですべてのバイトを返す null バイト数。</param>
        <param name="rangeContentMD5">場合に設定<c>true</c>、指定した範囲に MD5 ヘッダーを要求します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            指定された範囲のプロパティとメタデータと共に、ファイルの内容を返す web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, offset, count, rangeContentMD5, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="offset">コンテンツを返すを開始するバイト オフセットです。</param>
        <param name="count">戻り値、またはファイルの末尾まですべてのバイトを返す null バイト数。</param>
        <param name="rangeContentMD5">場合に設定<c>true</c>、指定した範囲に MD5 ヘッダーを要求します。</param>
        <param name="shareSnapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            指定された範囲のプロパティとメタデータと共に、ファイルの内容を返す web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルのユーザー定義メタデータを返す web 要求を構築します。
            </summary>
        <returns>操作を実行するための web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="shareSnapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルのユーザー定義メタデータを返す web 要求を構築します。
            </summary>
        <returns>操作を実行するための web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルのシステム プロパティを返すための web 要求を構築します。
            </summary>
        <returns>操作を実行するための web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="shareSnapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルのシステム プロパティを返すための web 要求を構築します。
            </summary>
        <returns>操作を実行するための web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />ファイル サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ファイル サービスのプロパティを取得する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges (uri, timeout, offset, count, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="offset">一覧のファイルにどのデータ範囲の範囲の開始オフセット (バイト単位)。</param>
        <param name="count">一覧のファイルにどのデータ範囲の範囲の長さ (バイト単位)。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルの有効な範囲の一覧を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges (uri, timeout, offset, count, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="offset">一覧のファイルにどのデータ範囲の範囲の開始オフセット (バイト単位)。</param>
        <param name="count">一覧のファイルにどのデータ範囲の範囲の長さ (バイト単位)。</param>
        <param name="shareSnapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルの有効な範囲の一覧を返す web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutRange">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutRange (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileRange fileRange, Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite fileRangeWrite, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutRange(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileRange fileRange, valuetype Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite fileRangeWrite, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.PutRange(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileRange,Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutRange : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileRange * Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.PutRange (uri, timeout, fileRange, fileRangeWrite, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="fileRange" Type="Microsoft.WindowsAzure.Storage.File.FileRange" />
        <Parameter Name="fileRangeWrite" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="fileRange">開始時刻と終了オフセット。</param>
        <param name="fileRangeWrite">ファイルへの書き込みまたは一連の範囲をクリアするおかどうかが記述するアクション。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            記述したり、ファイル内のページの範囲をクリアする web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Resize (Uri uri, Nullable&lt;int&gt; timeout, long newFileSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Resize(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int64 newFileSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Resize(System.Uri,System.Nullable{System.Int32},System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Resize : Uri * Nullable&lt;int&gt; * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Resize (uri, timeout, newFileSize, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="newFileSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="newFileSize">新しいファイル サイズ。 このパラメーターに設定<c>null</c>既存のファイル サイズが維持されます。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルのサイズを変更する web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ユーザー定義のメタデータ ファイルを設定する web 要求を構築します。
            </summary>
        <returns>操作を実行するための web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">ファイルの絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="properties">ファイルのプロパティです。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            ファイルのシステム プロパティを設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />ファイル サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ファイル サービスのプロパティを設定する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As FileServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> オブジェクト。</param>
        <param name="outputStream"><see cref="T:System.IO.Stream" />書式設定されたプロパティが書き込まれるオブジェクト。</param>
        <summary>
            ファイル サービスのプロパティを XML 形式で、ストリームに書き込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>