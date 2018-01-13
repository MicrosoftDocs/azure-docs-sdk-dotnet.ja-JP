<Type Name="ContainerHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class ContainerHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type ContainerHttpResponseParsers = class" />
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
            一連の Blob サービスからコンテナーの応答を解析するためのメソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType GetAcl (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType GetAcl(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.GetAcl(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetAcl (response As HttpWebResponse) As BlobContainerPublicAccessType" />
      <MemberSignature Language="F#" Value="static member GetAcl : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.GetAcl response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            応答からコンテナーの ACL を取得します。
            </summary>
        <returns>コンテナーのパブリック アクセス レベルを示す値。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.GetMetadata response" />
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
        <returns>A<see cref="T:System.Collections.Generic.IDictionary`2" />のメタデータ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties GetProperties (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties GetProperties(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.GetProperties(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetProperties (response As HttpWebResponse) As BlobContainerProperties" />
      <MemberSignature Language="F#" Value="static member GetProperties : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.GetProperties response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContainerProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            応答からコンテナーのプロパティを取得します。
            </summary>
        <returns>コンテナーの属性です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.GetRequestId response" />
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
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As BlobContainerPermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPermissions" />
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