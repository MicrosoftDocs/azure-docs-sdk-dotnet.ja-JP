<Type Name="FileHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class FileHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class FileHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type FileHttpResponseParsers = class" />
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
            ファイル サービス内のファイルに対する操作に対する応答を解析するメソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyAttributes">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.CopyState GetCopyAttributes (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Blob.CopyState GetCopyAttributes(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.GetCopyAttributes(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetCopyAttributes (response As HttpWebResponse) As CopyState" />
      <MemberSignature Language="F#" Value="static member GetCopyAttributes : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.CopyState" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.GetCopyAttributes response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CopyState</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">HTTP web 応答です。</param>
        <summary>
            抽出、 <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyState" /> web 応答のヘッダーからのオブジェクト。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyState" />オブジェクト、または<c>null</c> web 応答に状態コピーにはが含まれていない場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.GetMetadata response" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.FileProperties GetProperties (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.File.FileProperties GetProperties(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.GetProperties(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetProperties (response As HttpWebResponse) As FileProperties" />
      <MemberSignature Language="F#" Value="static member GetProperties : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.File.FileProperties" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.GetProperties response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            応答からのファイルのプロパティを取得します。
            </summary>
        <returns>ファイルのプロパティです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.GetRequestId response" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties ReadServiceProperties (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties ReadServiceProperties(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.ReadServiceProperties(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceProperties (inputStream As Stream) As FileServiceProperties" />
      <MemberSignature Language="F#" Value="static member ReadServiceProperties : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.ReadServiceProperties inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties</ReturnType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.ReadServiceStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceStats (inputStream As Stream) As ServiceStats" />
      <MemberSignature Language="F#" Value="static member ReadServiceStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpResponseParsers.ReadServiceStats inputStream" />
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
  </Members>
</Type>