<Type Name="QueueHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class QueueHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueueHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type QueueHttpWebRequestFactory = class" />
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
            キュー サービスでキューを管理する web 要求を構築するためのファクトリ クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AddMessage (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;int&gt; timeToLiveInSeconds, Nullable&lt;int&gt; visibilityTimeoutInSeconds, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AddMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; timeToLiveInSeconds, valuetype System.Nullable`1&lt;int32&gt; visibilityTimeoutInSeconds, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AddMessage : Uri * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage (uri, timeout, timeToLiveInSeconds, visibilityTimeoutInSeconds, operationContext)" />
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
        <Parameter Name="timeToLiveInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="timeToLiveInSeconds">有効期限を秒単位でメッセージです。</param>
        <param name="visibilityTimeoutInSeconds">によってメッセージが表示されなくなります、秒単位で時間の長さ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューのメッセージを追加する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AddMessage (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;int&gt; timeToLiveInSeconds, Nullable&lt;int&gt; visibilityTimeoutInSeconds, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AddMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; timeToLiveInSeconds, valuetype System.Nullable`1&lt;int32&gt; visibilityTimeoutInSeconds, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AddMessage : Uri * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage (uri, timeout, timeToLiveInSeconds, visibilityTimeoutInSeconds, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeToLiveInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="timeToLiveInSeconds">有効期限を秒単位でメッセージです。</param>
        <param name="visibilityTimeoutInSeconds">によってメッセージが表示されなくなります、秒単位で時間の長さ。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューのメッセージを追加する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
    <Member MemberName="ClearMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ClearMessages (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ClearMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ClearMessages : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages (uri, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キュー内のすべてのメッセージを消去する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ClearMessages (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ClearMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ClearMessages : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キュー内のすべてのメッセージを消去する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create (uri, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            新しいキューを作成する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            新しいキューを作成する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete (uri, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューおよびすべての内部にメッセージを削除する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューおよびすべての内部にメッセージを削除する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest DeleteMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest DeleteMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member DeleteMessage : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage (uri, timeout, popReceipt, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />更新メッセージへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="popReceipt">メッセージの popreceipt を指定する文字列。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            メッセージを更新する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest DeleteMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest DeleteMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member DeleteMessage : Uri * Nullable&lt;int&gt; * string * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage (uri, timeout, popReceipt, useVersionHeader, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />更新メッセージへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="popReceipt">メッセージの popreceipt を指定する文字列。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            メッセージを更新する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl (uri, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューの ACL を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューの ACL を返す web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMessages : Uri * Nullable&lt;int&gt; * int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages (uri, timeout, numberOfMessages, visibilityTimeout, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="numberOfMessages">取得するメッセージの数を指定する整数。</param>
        <param name="visibilityTimeout">A<see cref="T:System.TimeSpan" />表示タイムアウトを指定する値。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューからメッセージを取得する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Nullable&lt;TimeSpan&gt; visibilityTimeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Nullable{System.TimeSpan},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMessages : Uri * Nullable&lt;int&gt; * int * Nullable&lt;TimeSpan&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages (uri, timeout, numberOfMessages, visibilityTimeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="numberOfMessages">取得するメッセージの数を指定する整数。</param>
        <param name="visibilityTimeout">A<see cref="T:System.TimeSpan" />表示タイムアウトを指定する値。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューからメッセージを取得する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata (uri, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            このキューのユーザー定義メタデータを返す web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            このキューのユーザー定義メタデータを返す web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キュー サービスのプロパティを取得する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キュー サービスの統計情報を取得する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, operationContext)" />
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
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="listingContext"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> オブジェクト。</param>
        <param name="detailsIncluded">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />リスト、キューのメタデータを返すかどうかを示す列挙値。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            このストレージ アカウント内のすべてのキューの一覧が返されますへの web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, useVersionHeader, operationContext)" />
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
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="listingContext"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> オブジェクト。</param>
        <param name="detailsIncluded">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />リスト、キューのメタデータを返すかどうかを示す列挙値。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            このストレージ アカウント内のすべてのキューの一覧が返されますへの web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PeekMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PeekMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages(System.Uri,System.Nullable{System.Int32},System.Int32,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PeekMessages : Uri * Nullable&lt;int&gt; * int * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages (uri, timeout, numberOfMessages, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="numberOfMessages">ここに表示するメッセージの数を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューからメッセージをピークする web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PeekMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PeekMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PeekMessages : Uri * Nullable&lt;int&gt; * int * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages (uri, timeout, numberOfMessages, useVersionHeader, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="numberOfMessages">ここに表示するメッセージの数を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューからメッセージをピークする web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl (uri, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューの ACL を設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューの ACL を設定する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata (uri, timeout, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューのユーザー定義メタデータを設定する web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔を指定する整数。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キューのユーザー定義メタデータを設定する web 要求を生成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <param name="uri">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</param>
        <param name="builder">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            キュー サービスのプロパティを設定する web 要求を作成します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest UpdateMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, int visibilityTimeoutInSeconds, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest UpdateMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, int32 visibilityTimeoutInSeconds, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Int32,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member UpdateMessage : Uri * Nullable&lt;int&gt; * string * int * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage (uri, timeout, popReceipt, visibilityTimeoutInSeconds, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Int32" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />更新メッセージへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="popReceipt">メッセージの popreceipt を指定する文字列。</param>
        <param name="visibilityTimeoutInSeconds">によってメッセージが表示されなくなります、秒単位で時間の長さ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            メッセージを更新する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest UpdateMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, int visibilityTimeoutInSeconds, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest UpdateMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, int32 visibilityTimeoutInSeconds, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Int32,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member UpdateMessage : Uri * Nullable&lt;int&gt; * string * int * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage (uri, timeout, popReceipt, visibilityTimeoutInSeconds, useVersionHeader, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Int32" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">A<see cref="T:System.Uri" />更新メッセージへの絶対 URI を指定します。</param>
        <param name="timeout">サーバー タイムアウト間隔 (秒)。</param>
        <param name="popReceipt">メッセージの popreceipt を指定する文字列。</param>
        <param name="visibilityTimeoutInSeconds">によってメッセージが表示されなくなります、秒単位で時間の長さ。</param>
        <param name="useVersionHeader">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            メッセージを更新する web 要求を構築します。
            </summary>
        <returns><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
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
            キュー サービス プロパティを XML 形式で、ストリームに書き込みます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>