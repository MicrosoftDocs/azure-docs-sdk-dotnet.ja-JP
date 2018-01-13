<Type Name="BlobHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class BlobHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BlobHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type BlobHttpWebRequestFactory = class" />
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
            Blob サービスの HTTP web 要求を構築するためのファクトリ クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbortCopy">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AbortCopy (Uri uri, Nullable&lt;int&gt; timeout, string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AbortCopy(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AbortCopy(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AbortCopy : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AbortCopy (uri, timeout, copyId, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="copyId">中止するコピー操作の ID 文字列です。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 リース条件のみが、この操作でサポートされます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            コピー操作を中止する web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortCopy">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AbortCopy (Uri uri, Nullable&lt;int&gt; timeout, string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AbortCopy(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AbortCopy(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AbortCopy : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AbortCopy (uri, timeout, copyId, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <param name="request"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</param>
        <param name="metadata">A<see cref="T:System.Collections.Generic.Dictionary`2" />ユーザー定義メタデータを含むオブジェクト。</param>
        <summary>
            ユーザー定義メタデータを要求に 1 つまたは複数の名前と値のペアとして追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <param name="request"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</param>
        <param name="name">メタデータ名を含む文字列。</param>
        <param name="value">メタデータ値を含む文字列。</param>
        <summary>
            ユーザー定義メタデータを要求に 1 つの名前と値のペアとして追加します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlock">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AppendBlock (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AppendBlock(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AppendBlock(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AppendBlock : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AppendBlock (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にブロックをコミットする web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlock">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AppendBlock (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AppendBlock(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AppendBlock(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AppendBlock : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AppendBlock (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            追加 blob にブロックをコミットする web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom (uri, timeout, source, sourceAccessCondition, destAccessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="source">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、コピー先 blob に満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob またはファイルを別の blob にコピーする web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom (uri, timeout, source, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="source">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、コピー先 blob に満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob またはファイルを別の blob にコピーする web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, bool incrementalCopy, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, bool incrementalCopy, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom (uri, timeout, source, incrementalCopy, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="incrementalCopy" Type="System.Boolean" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="source">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</param>
        <param name="incrementalCopy">これは、増分のコピーであるかどうかを示すブール値。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、コピー先 blob に満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob またはファイルを別の blob にコピーする web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, bool incrementalCopy, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, bool incrementalCopy, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,System.Boolean,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * bool * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom (uri, timeout, source, incrementalCopy, premiumPageBlobTier, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="incrementalCopy" Type="System.Boolean" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="source">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</param>
        <param name="incrementalCopy">これは、増分のコピーであるかどうかを示すブール値。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="sourceAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</param>
        <param name="destAccessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、コピー先 blob に満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob またはファイルを別の blob にコピーする web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Delete (uri, timeout, snapshot, deleteSnapshotsOption, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />かどうかのみを削除する blob のスナップショットのみ、またはその両方を示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob を削除する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Delete (uri, timeout, snapshot, deleteSnapshotsOption, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />かどうかのみを削除する blob のスナップショットのみ、またはその両方を示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob を削除する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get (uri, timeout, snapshot, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのバージョンを指定します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のコンテンツ、プロパティ、およびメタデータを取得する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのバージョンを指定します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のコンテンツ、プロパティ、およびメタデータを取得する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get (uri, timeout, snapshot, offset, count, rangeContentMD5, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのバージョンを指定します。</param>
        <param name="offset">コンテンツを返すを開始するバイト オフセットです。</param>
        <param name="count">戻るには、バイト数または<c>null</c>を blob の末尾までのすべてのバイトを返します。</param>
        <param name="rangeContentMD5">場合に設定<c>true</c>、指定した範囲の MD5 ヘッダーが要求されました。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            そのプロパティおよびメタデータの blob のコンテンツの指定された範囲を返す web 要求を構築します。
            </summary>
        <returns>
            使用して、操作を実行する web 要求。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get (uri, timeout, snapshot, offset, count, rangeContentMD5, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのバージョンを指定します。</param>
        <param name="offset">コンテンツを返すを開始するバイト オフセットです。</param>
        <param name="count">戻るには、バイト数または<c>null</c>を blob の末尾までのすべてのバイトを返します。</param>
        <param name="rangeContentMD5">場合に設定<c>true</c>、指定した範囲の MD5 ヘッダーが要求されました。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            そのプロパティおよびメタデータの blob のコンテンツの指定された範囲を返す web 要求を構築します。
            </summary>
        <returns>
            使用して、操作を実行する web 要求。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlockList">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetBlockList (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter typesOfBlocks, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetBlockList(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter typesOfBlocks, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetBlockList(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetBlockList : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetBlockList (uri, timeout, snapshot, typesOfBlocks, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="typesOfBlocks" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="typesOfBlocks"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> 列挙値。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ブロック blob のブロックの一覧を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlockList">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetBlockList (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter typesOfBlocks, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetBlockList(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter typesOfBlocks, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetBlockList(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetBlockList : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetBlockList (uri, timeout, snapshot, typesOfBlocks, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="typesOfBlocks" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="typesOfBlocks"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> 列挙値。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ブロック blob のブロックの一覧を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetMetadata (uri, timeout, snapshot, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のユーザー定義メタデータを返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetMetadata (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のユーザー定義メタデータを返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetPageRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetPageRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetPageRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRanges (uri, timeout, snapshot, offset, count, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="offset">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="count">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob の有効なページ範囲の一覧を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetPageRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetPageRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetPageRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRanges (uri, timeout, snapshot, offset, count, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="offset">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="count">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob の有効なページ範囲の一覧を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesDiff">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetPageRangesDiff (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, DateTimeOffset previousSnapshotTime, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetPageRangesDiff(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.DateTimeOffset previousSnapshotTime, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRangesDiff(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.DateTimeOffset,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetPageRangesDiff : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRangesDiff (uri, timeout, snapshot, previousSnapshotTime, offset, count, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="previousSnapshotTime">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</param>
        <param name="offset">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="count">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。 512 の倍数である必要があります。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定したスナップショットとこのオブジェクトの間で異なるページ範囲のリストを返すための web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetProperties (uri, timeout, snapshot, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のシステム プロパティを返すための web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetProperties (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="snapshot">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のシステム プロパティを返すための web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <param name="uri">A <see cref="T:System.Uri" /> Blob サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob サービスのプロパティを取得する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
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
        <param name="uri">A <see cref="T:System.Uri" /> Blob サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob サービスの統計情報を取得する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Lease (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, Nullable&lt;int&gt; leaseDuration, Nullable&lt;int&gt; leaseBreakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Lease(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, valuetype System.Nullable`1&lt;int32&gt; leaseDuration, valuetype System.Nullable`1&lt;int32&gt; leaseBreakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Lease(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.LeaseAction,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Lease : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.LeaseAction * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Lease (uri, timeout, action, proposedLeaseId, leaseDuration, leaseBreakPeriod, accessCondition, operationContext)" />
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
        <Parameter Name="action" Type="Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="leaseDuration" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="leaseBreakPeriod" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="action">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />リース操作を実行することを示す列挙値。</param>
        <param name="proposedLeaseId">取得の結果の提案または操作を変更するには、リース ID を指定する文字列または<c>null</c>取得操作の ID が推奨されていない場合。 このパラメーターを指定する必要があります<c>null</c>の書き換え、リリース、および中断操作。</param>
        <param name="leaseDuration">リース期間を秒単位での操作を取得します。
            -1 は無限の期間が指定されます。 これは、値には<c>null</c>更新、変更、リリース、および操作を中断します。</param>
        <param name="leaseBreakPeriod">秒単位、リースを中断する前に中断操作の後で、待機する時間の量。
            これは、する場合<c>null</c>既定の時間が使用されます。 これは、値には<c>null</c>の取得、更新、変更、および操作を解放します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            使用して取得、更新、変更、リリース、または blob のリースを中断する web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Lease (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, Nullable&lt;int&gt; leaseDuration, Nullable&lt;int&gt; leaseBreakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Lease(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, valuetype System.Nullable`1&lt;int32&gt; leaseDuration, valuetype System.Nullable`1&lt;int32&gt; leaseBreakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Lease(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.LeaseAction,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Lease : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.LeaseAction * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Lease (uri, timeout, action, proposedLeaseId, leaseDuration, leaseBreakPeriod, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="action" Type="Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="leaseDuration" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="leaseBreakPeriod" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="action">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />リース操作を実行することを示す列挙値。</param>
        <param name="proposedLeaseId">取得の結果の提案または操作を変更するには、リース ID を指定する文字列または<c>null</c>取得操作の ID が推奨されていない場合。 このパラメーターを指定する必要があります<c>null</c>の書き換え、リリース、および中断操作。</param>
        <param name="leaseDuration">リース期間を秒単位での操作を取得します。
            -1 は無限の期間が指定されます。 これは、値には<c>null</c>更新、変更、リリース、および操作を中断します。</param>
        <param name="leaseBreakPeriod">秒単位、リースを中断する前に中断操作の後で、待機する時間の量。
            これは、する場合<c>null</c>既定の時間が使用されます。 これは、値には<c>null</c>の取得、更新、変更、および操作を解放します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            使用して取得、更新、変更、リリース、または blob のリースを中断する web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Put">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Put (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.Blob.BlobType blobType, long pageBlobSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Put(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType blobType, int64 pageBlobSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Put(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.Blob.BlobType,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Put : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.Blob.BlobType * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Put (uri, timeout, properties, blobType, pageBlobSize, accessCondition, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="blobType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobType" />
        <Parameter Name="pageBlobSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> オブジェクト。</param>
        <param name="blobType"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobType" /> 列挙値。</param>
        <param name="pageBlobSize">ページ blob の場合、blob のサイズ。 ブロック blob では、このパラメーターは無視されます。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            新しいブロック blob またはページ blob を作成または既存のブロック blob のコンテンツを更新する web 要求を構築します。 
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Put">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Put (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.Blob.BlobType blobType, long pageBlobSize, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Put(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType blobType, int64 pageBlobSize, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Put(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.Blob.BlobType,System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Put : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.Blob.BlobType * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Put (uri, timeout, properties, blobType, pageBlobSize, premiumPageBlobTier, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="blobType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobType" />
        <Parameter Name="pageBlobSize" Type="System.Int64" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> オブジェクト。</param>
        <param name="blobType"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobType" /> 列挙値。</param>
        <param name="pageBlobSize">ページ blob の場合、blob のサイズ。 ブロック blob では、このパラメーターは無視されます。</param>
        <param name="premiumPageBlobTier">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            新しいブロック blob またはページ blob を作成または既存のブロック blob のコンテンツを更新する web 要求を構築します。 
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlock">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutBlock (Uri uri, Nullable&lt;int&gt; timeout, string blockId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutBlock(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string blockId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlock(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutBlock : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlock (uri, timeout, blockId, accessCondition, operationContext)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="blockId">このブロックのブロック ID を指定する文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ブロック blob に書き込み、ブロックへの web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlock">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutBlock (Uri uri, Nullable&lt;int&gt; timeout, string blockId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutBlock(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string blockId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlock(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutBlock : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlock (uri, timeout, blockId, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="blockId">このブロックのブロック ID を指定する文字列。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ブロック blob に書き込み、ブロックへの web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockList">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutBlockList (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutBlockList(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlockList(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutBlockList : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlockList (uri, timeout, properties, accessCondition, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="properties">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> blob に対して設定するプロパティを指定するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            作成またはブロック リストをコミットすることによって blob を更新する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockList">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutBlockList (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutBlockList(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlockList(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutBlockList : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlockList (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="properties">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> blob に対して設定するプロパティを指定するオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            作成またはブロック リストをコミットすることによって blob を更新する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutPage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutPage (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.PageRange pageRange, Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite pageWrite, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutPage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.PageRange pageRange, valuetype Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite pageWrite, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutPage(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.PageRange,Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutPage : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.PageRange * Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutPage (uri, timeout, pageRange, pageWrite, accessCondition, operationContext)" />
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
        <Parameter Name="pageRange" Type="Microsoft.WindowsAzure.Storage.Blob.PageRange" />
        <Parameter Name="pageWrite" Type="Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="pageRange"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> オブジェクト。</param>
        <param name="pageWrite">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" />ページ blob に対して実行する操作を表す列挙値。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            記述したり、ページ blob のページの範囲をクリアする web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutPage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutPage (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.PageRange pageRange, Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite pageWrite, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutPage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.PageRange pageRange, valuetype Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite pageWrite, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutPage(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.PageRange,Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutPage : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.PageRange * Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutPage (uri, timeout, pageRange, pageWrite, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="pageRange" Type="Microsoft.WindowsAzure.Storage.Blob.PageRange" />
        <Parameter Name="pageWrite" Type="Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="pageRange"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> オブジェクト。</param>
        <param name="pageWrite">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" />ページ blob に対して実行する操作を表す列挙値。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            記述したり、ページ blob のページの範囲をクリアする web 要求を構築します。
            </summary>
        <returns>
            使用して、操作を実行する web 要求。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Resize (Uri uri, Nullable&lt;int&gt; timeout, long newBlobSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Resize(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int64 newBlobSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Resize(System.Uri,System.Nullable{System.Int32},System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Resize : Uri * Nullable&lt;int&gt; * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Resize (uri, timeout, newBlobSize, accessCondition, operationContext)" />
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
        <Parameter Name="newBlobSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="newBlobSize">新しい blob のサイズ、ページ blob の場合。 このパラメーターに設定<c>null</c>既存の blob のサイズを保持します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob のサイズを変更する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Resize (Uri uri, Nullable&lt;int&gt; timeout, long newBlobSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Resize(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int64 newBlobSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Resize(System.Uri,System.Nullable{System.Int32},System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Resize : Uri * Nullable&lt;int&gt; * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Resize (uri, timeout, newBlobSize, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="newBlobSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="newBlobSize">新しい blob のサイズ、ページ blob の場合。 このパラメーターに設定<c>null</c>既存の blob のサイズを保持します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob のサイズを変更する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetBlobTier">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetBlobTier (Uri uri, Nullable&lt;int&gt; timeout, string blobTier, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetBlobTier(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string blobTier, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetBlobTier(System.Uri,System.Nullable{System.Int32},System.String,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetBlobTier : Uri * Nullable&lt;int&gt; * string * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetBlobTier (uri, timeout, blobTier, useVersionHeader, operationContext)" />
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
        <Parameter Name="blobTier" Type="System.String" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="blobTier">文字列として設定する blob 層です。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob の層に設定する web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のユーザー定義メタデータを設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のユーザー定義メタデータを設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="properties">Blob のプロパティです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のシステム プロパティを設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="properties">Blob のプロパティです。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のシステム プロパティを設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumber">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetSequenceNumber (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetSequenceNumber(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetSequenceNumber(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetSequenceNumber : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetSequenceNumber (uri, timeout, sequenceNumberAction, sequenceNumber, accessCondition, operationContext)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合、この操作は、増分処理します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob のシーケンス番号を設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumber">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetSequenceNumber (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetSequenceNumber(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetSequenceNumber(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetSequenceNumber : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetSequenceNumber (uri, timeout, sequenceNumberAction, sequenceNumber, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="sequenceNumberAction">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</param>
        <param name="sequenceNumber">シーケンス番号。 このパラメーターに設定<c>null</c>場合、この操作は、増分処理します。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ページ blob のシーケンス番号を設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <param name="uri">A <see cref="T:System.Uri" /> Blob サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob サービスのプロパティを設定する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Snapshot (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Snapshot(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Snapshot(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Snapshot : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Snapshot (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のスナップショットを作成する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Snapshot (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Snapshot(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Snapshot(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Snapshot : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Snapshot (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            Blob のスナップショットを作成する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
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
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</param>
        <param name="outputStream"><see cref="T:System.IO.Stream" />書式設定されたプロパティが書き込まれるオブジェクト。</param>
        <summary>
            Blob サービスのプロパティを XML 形式で、ストリームに書き込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>