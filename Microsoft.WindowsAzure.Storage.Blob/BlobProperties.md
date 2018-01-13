<Type Name="BlobProperties" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobProperties">
  <TypeSignature Language="C#" Value="public sealed class BlobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobProperties" />
  <TypeSignature Language="F#" Value="type BlobProperties = class" />
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
            Blob のシステム プロパティを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobProperties (Microsoft.WindowsAzure.Storage.Blob.BlobProperties other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Blob.BlobProperties other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.#ctor(Microsoft.WindowsAzure.Storage.Blob.BlobProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As BlobProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.BlobProperties : Microsoft.WindowsAzure.Storage.Blob.BlobProperties -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobProperties" Usage="new Microsoft.WindowsAzure.Storage.Blob.BlobProperties other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
      </Parameters>
      <Docs>
        <param name="other"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />クラスは、既存のインスタンスに基づいています。
            </summary>
        <remarks>ベース blob に関連付けられたリースはスナップショットにコピーされないため、リース関連のプロパティは複製されません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlobCommittedBlockCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AppendBlobCommittedBlockCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AppendBlobCommittedBlockCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.AppendBlobCommittedBlockCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppendBlobCommittedBlockCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AppendBlobCommittedBlockCount : Nullable&lt;int&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.AppendBlobCommittedBlockCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob が、追加 blob の場合は、コミット後のブロックの数を取得します。
            </summary>
        <value>コミット後のブロックの数を格納する整数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobTierInferred">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; BlobTierInferred { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; BlobTierInferred" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobTierInferred" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobTierInferred As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.BlobTierInferred : Nullable&lt;bool&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobTierInferred" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob の層が推論されているかどうかを示す値を取得します。
            </summary>
        <value>Bool を表す場合は、blob の層が推論されました。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobTierLastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; BlobTierLastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; BlobTierLastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobTierLastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobTierLastModifiedTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.BlobTierLastModifiedTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobTierLastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob の層が前回変更された UTC 値として表されるときの時間を取得します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />と blob の層が、日時を UTC 形式での時刻を含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobType As BlobType" />
      <MemberSignature Language="F#" Value="member this.BlobType : Microsoft.WindowsAzure.Storage.Blob.BlobType" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob の種類を取得します。
            </summary>
        <value>A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.BlobType" /> blob の種類を示すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheControl">
      <MemberSignature Language="C#" Value="public string CacheControl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CacheControl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.CacheControl" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheControl As String" />
      <MemberSignature Language="F#" Value="member this.CacheControl : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.CacheControl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または格納されている blob の cache-control 値を設定します。
            </summary>
        <value>Blob の cache-control 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentDisposition">
      <MemberSignature Language="C#" Value="public string ContentDisposition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentDisposition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentDisposition" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentDisposition As String" />
      <MemberSignature Language="F#" Value="member this.ContentDisposition : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentDisposition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または格納されている blob の content-disposition 値を設定します。
            </summary>
        <value>Blob の content-disposition 値を含む文字列。</value>
        <remarks>
            このプロパティが設定されていないかどうか、blob をそれを返します<c>null</c>です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または格納されている blob の content-encoding 値を設定します。
            </summary>
        <value>Blob の content-encoding 値を含む文字列。</value>
        <remarks>
            このプロパティが設定されていないかどうか、blob をそれを返します<c>null</c>です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLanguage">
      <MemberSignature Language="C#" Value="public string ContentLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLanguage As String" />
      <MemberSignature Language="F#" Value="member this.ContentLanguage : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または格納されている blob の content-language 値を設定します。
            </summary>
        <value>Blob の content-language 値を含む文字列。</value>
        <remarks>
            このプロパティが設定されていないかどうか、blob をそれを返します<c>null</c>です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentMD5">
      <MemberSignature Language="C#" Value="public string ContentMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentMD5 As String" />
      <MemberSignature Language="F#" Value="member this.ContentMD5 : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または格納されている blob の content-md5 値を設定します。
            </summary>
        <value>Blob の content-md5 ハッシュを含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または格納されている blob の content-type 値を設定します。
            </summary>
        <value>Blob の content-type 値を含む文字列。</value>
        <remarks>
            このプロパティが設定されていないかどうか、blob をそれを返します<c>null</c>です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob の ETag 値を取得します。
            </summary>
        <value>Blob の ETag 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIncrementalCopy">
      <MemberSignature Language="C#" Value="public bool IsIncrementalCopy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsIncrementalCopy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.IsIncrementalCopy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsIncrementalCopy As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsIncrementalCopy : bool" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.IsIncrementalCopy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この blob は、増分のコピーであるかどうかを示す値を取得します。
            </summary>
        <value>Blob が増分のコピーである場合を表すブール値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsServerEncrypted">
      <MemberSignature Language="C#" Value="public bool IsServerEncrypted { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsServerEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.IsServerEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsServerEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsServerEncrypted : bool" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.IsServerEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob のサーバー側暗号化の状態を取得します。
            </summary>
        <value>Blob のサーバー側の暗号化の状態を表すブール値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、blob の最終更新時刻が UTC 値として表されます。
            </summary>
        <value>A <see cref="T:System.DateTimeOffset" /> UTC 形式で、blob の最終更新時刻を含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseDuration LeaseDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseDuration LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseDuration As LeaseDuration" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : Microsoft.WindowsAzure.Storage.Blob.LeaseDuration" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseDuration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob のリース期間を取得します。
            </summary>
        <value>A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseDuration" /> blob のリース期間を示すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseState">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseState LeaseState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState LeaseState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseState As LeaseState" />
      <MemberSignature Language="F#" Value="member this.LeaseState : Microsoft.WindowsAzure.Storage.Blob.LeaseState" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob のリースの状態を取得します。
            </summary>
        <value>A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseState" /> blob のリースの状態を示すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseStatus">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.LeaseStatus LeaseStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseStatus LeaseStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseStatus As LeaseStatus" />
      <MemberSignature Language="F#" Value="member this.LeaseStatus : Microsoft.WindowsAzure.Storage.Blob.LeaseStatus" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob のリース ステータスを取得します。
            </summary>
        <value>A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.LeaseStatus" /> blob のリース ステータスを示すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob のサイズをバイト単位で取得します。
            </summary>
        <value>Blob のサイズ (バイト単位) を表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PageBlobSequenceNumber">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PageBlobSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PageBlobSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PageBlobSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PageBlobSequenceNumber As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PageBlobSequenceNumber : Nullable&lt;int64&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PageBlobSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob がページ blob の場合は、blob の現在のシーケンス番号を取得します。
            </summary>
        <value>Blob の現在のシーケンス番号を表す long 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PremiumPageBlobTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; PremiumPageBlobTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; PremiumPageBlobTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PremiumPageBlobTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PremiumPageBlobTier As Nullable(Of PremiumPageBlobTier)" />
      <MemberSignature Language="F#" Value="member this.PremiumPageBlobTier : Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PremiumPageBlobTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Premium ページ blob の層を示す値を取得します。
            </summary>
        <value>A<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.PremiumPageBlobTier" />をページ blob の層を示すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RehydrationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus&gt; RehydrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus&gt; RehydrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.RehydrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RehydrationStatus As Nullable(Of RehydrationStatus)" />
      <MemberSignature Language="F#" Value="member this.RehydrationStatus : Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.RehydrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.RehydrationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Blob されていると、blob の層の rehdrated アーカイブから復元が完了したらを示す値を取得します。
            </summary>
        <value>A <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.RehydrationStatus" /> blob の状態を復元します。</value>
        <remarks>このバージョンのライブラリでブロック blob のみに適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="StandardBlobTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier&gt; StandardBlobTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier&gt; StandardBlobTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.StandardBlobTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StandardBlobTier As Nullable(Of StandardBlobTier)" />
      <MemberSignature Language="F#" Value="member this.StandardBlobTier : Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobProperties.StandardBlobTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.StandardBlobTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ブロック blob の層を示す値を取得します。
            </summary>
        <value>A<see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobProperties.StandardBlobTier" />をブロック blob の層を示すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>