<Type Name="QueueHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class QueueHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueueHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type QueueHttpResponseParsers = class" />
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
            キュー サービスのキュー データを含む応答を解析するためのメソッドのセットを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApproximateMessageCount">
      <MemberSignature Language="C#" Value="public static string GetApproximateMessageCount (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetApproximateMessageCount(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetApproximateMessageCount(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetApproximateMessageCount (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetApproximateMessageCount : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetApproximateMessageCount response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            キューのおおよそのメッセージ数を取得します。
            </summary>
        <returns>キューのおおよその数。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetMetadata response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">サーバーからの応答。</param>
        <summary>
            ユーザー定義メタデータを取得します。
            </summary>
        <returns>型のオブジェクト<see cref="T:System.Collections.IDictionary" />メタデータを含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextVisibleTime">
      <MemberSignature Language="C#" Value="public static DateTime GetNextVisibleTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype System.DateTime GetNextVisibleTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetNextVisibleTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNextVisibleTime (response As HttpWebResponse) As DateTime" />
      <MemberSignature Language="F#" Value="static member GetNextVisibleTime : System.Net.HttpWebResponse -&gt; DateTime" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetNextVisibleTime response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            Web 応答ヘッダーから、次回の可視性を抽出します。
            </summary>
        <returns>応答のヘッダーに格納されている次の可視性の時刻。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPopReceipt">
      <MemberSignature Language="C#" Value="public static string GetPopReceipt (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetPopReceipt(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetPopReceipt(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetPopReceipt (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetPopReceipt : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetPopReceipt response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            Popreceipt は、web 応答ヘッダーから抽出します。
            </summary>
        <returns>応答のヘッダーに格納されている popreceipt。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetRequestId response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            応答からの要求 ID を取得します。
            </summary>
        <returns>要求に関連付けられている一意の値。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceProperties(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceProperties (inputStream As Stream) As ServiceProperties" />
      <MemberSignature Language="F#" Value="static member ReadServiceProperties : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceProperties inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream">サービスのプロパティが読み取り元のストリーム。</param>
        <summary>
            サービスのプロパティをストリームから読み取ります。
            </summary>
        <returns>ストリームに格納されているサービスのプロパティです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceStats">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats ReadServiceStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats ReadServiceStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceStats (inputStream As Stream) As ServiceStats" />
      <MemberSignature Language="F#" Value="static member ReadServiceStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceStats inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream">サービスの統計情報を読み取り元のストリーム。</param>
        <summary>
            ストリームからサービスの統計情報を読み取ります。
            </summary>
        <returns>ストリームに格納されているサービスの統計情報です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As QueuePermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
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
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
      </Parameters>
      <Docs>
        <param name="inputStream">Xml 形式のポリシーのストリーム。</param>
        <param name="permissions">ポリシーが書き込まれるアクセス許可オブジェクト。</param>
        <summary>
            共有アクセス ポリシーを xml ストリームから読み取ります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>