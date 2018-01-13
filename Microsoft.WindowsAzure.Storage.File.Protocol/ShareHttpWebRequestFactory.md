<Type Name="ShareHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class ShareHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ShareHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ShareHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type ShareHttpWebRequestFactory = class" />
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
            操作の web 要求を構築するためのファクトリ クラスは、ファイル サービスで共有します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            新しい共有を作成する web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Microsoft.WindowsAzure.Storage.File.FileShareProperties properties, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, class Microsoft.WindowsAzure.Storage.File.FileShareProperties properties, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Create(System.Uri,Microsoft.WindowsAzure.Storage.File.FileShareProperties,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.WindowsAzure.Storage.File.FileShareProperties * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Create (uri, properties, timeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileShareProperties" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">共有の絶対 URI です。</param>
        <param name="properties">共有に設定するプロパティです。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            新しい共有を作成する web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            共有とその中のファイルをすべて削除する web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Delete (uri, timeout, snapshot, deleteSnapshotsOption, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="snapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />のみ、共有を削除するか、共有とすべてのスナップショットを削除するかどうかを示すオブジェクト。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            共有とその中のファイルをすべて削除する web 要求を構築します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetAcl (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />共有への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有の ACL を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            この共有のユーザー定義メタデータを返す web 要求を生成します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetMetadata (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="snapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            この共有のユーザー定義メタデータを返す web 要求を生成します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            この共有のユーザー定義のメタデータとプロパティを返す web 要求を生成します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetProperties (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="snapshot">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            この共有のユーザー定義のメタデータとプロパティを返す web 要求を生成します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetStats (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetStats(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetStats(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetStats : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetStats (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />共有を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有の統計情報を取得する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, useVersionHeader, operationContext)" />
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
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">アカウントの絶対 URI。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="listingContext">一覧作成操作のパラメーターのセット。</param>
        <param name="detailsIncluded">一覧を返す追加の詳細。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            このストレージ アカウント内のすべての共有の一覧が返されますへの web 要求を構築します。
            </summary>
        <returns>指定された操作の web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType publicAccess, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType publicAccess, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetAcl (uri, timeout, publicAccess, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="publicAccess" Type="Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />共有への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="publicAccess">共有のようにパブリック アクセスの種類。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有の ACL を設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">共有の絶対 URI です。</param>
        <param name="timeout">サーバー タイムアウト間隔。</param>
        <param name="accessCondition">要求に適用するアクセス条件。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</param>
        <summary>
            共有のユーザー定義メタデータを設定する web 要求を生成します。
            </summary>
        <returns>使用して、操作を実行する web 要求。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileShareProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileShareProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileShareProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileShareProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileShareProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />共有への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="properties">共有のプロパティです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のシステム プロパティを設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Snapshot (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Snapshot(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Snapshot(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Snapshot : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Snapshot (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />共有への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のスナップショットを作成する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>