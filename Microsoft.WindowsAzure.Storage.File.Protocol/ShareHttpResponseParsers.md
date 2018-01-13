<Type Name="ShareHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class ShareHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ShareHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class ShareHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type ShareHttpResponseParsers = class" />
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
            ファイル サービスで共有での操作に対する応答を解析中のメソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetMetadata response" />
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
        <returns>A<see cref="T:System.Collections.IDictionary" />のメタデータ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.FileShareProperties GetProperties (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.File.FileShareProperties GetProperties(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetProperties(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetProperties (response As HttpWebResponse) As FileShareProperties" />
      <MemberSignature Language="F#" Value="static member GetProperties : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.File.FileShareProperties" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetProperties response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileShareProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            応答から共有のプロパティを取得します。
            </summary>
        <returns>共有の属性です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetRequestId response" />
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
    <Member MemberName="GetSnapshotTime">
      <MemberSignature Language="C#" Value="public static string GetSnapshotTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetSnapshotTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetSnapshotTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSnapshotTime (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetSnapshotTime : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetSnapshotTime response" />
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
            応答から、スナップショットのタイムスタンプを取得します。
            </summary>
        <returns>スナップショットのタイムスタンプ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.FileSharePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As FileSharePermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.FileSharePermissions -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
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
    <Member MemberName="ReadShareStats">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats ReadShareStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats ReadShareStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadShareStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadShareStats (inputStream As Stream) As ShareStats" />
      <MemberSignature Language="F#" Value="static member ReadShareStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadShareStats inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream">共有の統計情報を読み取り元のストリーム。</param>
        <summary>
            読み取り、ストリームからの統計情報を共有します。
            </summary>
        <returns>ストリームに格納されている共有の統計情報です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>