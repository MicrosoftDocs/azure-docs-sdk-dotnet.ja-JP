<Type Name="BlobHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class BlobHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BlobHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type BlobHttpResponseParsers = class" />
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
            一連の Blob サービスから応答を含む blob データを解析するためのメソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyAttributes">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.CopyState GetCopyAttributes (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Blob.CopyState GetCopyAttributes(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetCopyAttributes(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetCopyAttributes (response As HttpWebResponse) As CopyState" />
      <MemberSignature Language="F#" Value="static member GetCopyAttributes : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.CopyState" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetCopyAttributes response" />
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
    <Member MemberName="GetIncrementalCopyStatus">
      <MemberSignature Language="C#" Value="public static bool GetIncrementalCopyStatus (string incrementalCopyHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool GetIncrementalCopyStatus(string incrementalCopyHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetIncrementalCopyStatus(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetIncrementalCopyStatus (incrementalCopyHeader As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member GetIncrementalCopyStatus : string -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetIncrementalCopyStatus incrementalCopyHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="incrementalCopyHeader" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="incrementalCopyHeader">Blob の増分のコピーのステータスを示す文字列します。</param>
        <summary>
            場合差分コピー内の blob を決定します。
            </summary>
        <returns>
          <c>true</c> blob が増分のコピーである場合または<c>false</c>しない場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseDuration">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.LeaseDuration GetLeaseDuration (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseDuration GetLeaseDuration(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseDuration(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLeaseDuration (response As HttpWebResponse) As LeaseDuration" />
      <MemberSignature Language="F#" Value="static member GetLeaseDuration : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.LeaseDuration" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseDuration response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseDuration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            リース期間は、web 応答から抽出します。
            </summary>
        <returns>A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseDuration" /> web 応答からの列挙。</returns>
        <remarks>適切なヘッダーが存在しない場合のステータス<see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseDuration.Unspecified" />が返されます。</remarks>
        <exception cref="T:System.ArgumentException">ヘッダーには、認識されない値が含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseId">
      <MemberSignature Language="C#" Value="public static string GetLeaseId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetLeaseId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLeaseId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetLeaseId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseId response" />
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
            Web 応答からのリース ID ヘッダーを抽出します。
            </summary>
        <returns>リース id です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseState">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.LeaseState GetLeaseState (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState GetLeaseState(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseState(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLeaseState (response As HttpWebResponse) As LeaseState" />
      <MemberSignature Language="F#" Value="static member GetLeaseState : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.LeaseState" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseState response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            リースの状態は、web 応答から抽出します。
            </summary>
        <returns>A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseState" /> web 応答からの列挙。</returns>
        <remarks>適切なヘッダーが存在しない場合のステータス<see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Unspecified" />が返されます。</remarks>
        <exception cref="T:System.ArgumentException">ヘッダーには、認識されない値が含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.LeaseStatus GetLeaseStatus (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseStatus GetLeaseStatus(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseStatus(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLeaseStatus (response As HttpWebResponse) As LeaseStatus" />
      <MemberSignature Language="F#" Value="static member GetLeaseStatus : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.LeaseStatus" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseStatus response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            リースの状態は、web 応答から抽出します。
            </summary>
        <returns>A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseStatus" /> web 応答からの列挙。</returns>
        <remarks>適切なヘッダーが存在しない場合のステータス<see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseStatus.Unspecified" />が返されます。</remarks>
        <exception cref="T:System.ArgumentException">ヘッダーには、認識されない値が含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetMetadata response" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.BlobProperties GetProperties (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Blob.BlobProperties GetProperties(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetProperties(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetProperties (response As HttpWebResponse) As BlobProperties" />
      <MemberSignature Language="F#" Value="static member GetProperties : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetProperties response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            応答から blob のプロパティを取得します。
            </summary>
        <returns>Blob のプロパティです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemainingLeaseTime">
      <MemberSignature Language="C#" Value="public static Nullable&lt;int&gt; GetRemainingLeaseTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype System.Nullable`1&lt;int32&gt; GetRemainingLeaseTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetRemainingLeaseTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRemainingLeaseTime (response As HttpWebResponse) As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="static member GetRemainingLeaseTime : System.Net.HttpWebResponse -&gt; Nullable&lt;int&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetRemainingLeaseTime response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response">Web 応答です。</param>
        <summary>
            残りのリース期間は、web 応答から抽出します。
            </summary>
        <returns>残りのリース時間 (秒)。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetRequestId response" />
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
    <Member MemberName="GetServerEncrypted">
      <MemberSignature Language="C#" Value="public static bool GetServerEncrypted (string encryptionHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool GetServerEncrypted(string encryptionHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetServerEncrypted(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetServerEncrypted (encryptionHeader As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member GetServerEncrypted : string -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetServerEncrypted encryptionHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptionHeader" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="encryptionHeader">サーバーの暗号化の状態を与える文字列。</param>
        <summary>
            Blob がサーバー側暗号化として表示されているかどうかを判断します。
            </summary>
        <returns>
          <c>true</c> blob が暗号化されている場合または<c>false</c>しない場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSnapshotTime">
      <MemberSignature Language="C#" Value="public static string GetSnapshotTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetSnapshotTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetSnapshotTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSnapshotTime (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetSnapshotTime : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetSnapshotTime response" />
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
    <Member MemberName="ReadServiceProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.ReadServiceProperties(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceProperties (inputStream As Stream) As ServiceProperties" />
      <MemberSignature Language="F#" Value="static member ReadServiceProperties : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.ReadServiceProperties inputStream" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.ReadServiceStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceStats (inputStream As Stream) As ServiceStats" />
      <MemberSignature Language="F#" Value="static member ReadServiceStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.ReadServiceStats inputStream" />
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