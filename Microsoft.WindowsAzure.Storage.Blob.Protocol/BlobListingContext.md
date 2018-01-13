<Type Name="BlobListingContext" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext">
  <TypeSignature Language="C#" Value="public sealed class BlobListingContext : Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobListingContext extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobListingContext&#xA;Inherits ListingContext" />
  <TypeSignature Language="F#" Value="type BlobListingContext = class&#xA;    inherit ListingContext" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Blob の操作を一覧表示するには、パラメーターのセットを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobListingContext (string prefix, Nullable&lt;int&gt; maxResults, string delimiter, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, string delimiter, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext.#ctor(System.String,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (prefix As String, maxResults As Nullable(Of Integer), delimiter As String, details As BlobListingDetails)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext : string * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext (prefix, maxResults, delimiter, details)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="delimiter" Type="System.String" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
      </Parameters>
      <Docs>
        <param name="prefix">Blob プレフィックスです。</param>
        <param name="maxResults">返される結果の最大数。</param>
        <param name="delimiter">Blob の区切り記号。</param>
        <param name="details">Include パラメーター。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext.Delimiter" />
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
            取得または blob の操作を一覧表示する区切り記号を設定します。
            </summary>
        <value>Blob の仮想の階層の走査に使用する区切り記号です。</value>
        <remarks>
            Delimiter パラメーターには、ユーザー定義の区切り記号を使用して blob 名前空間を走査する、呼び出し元が有効です。 このパラメーターを使用することは、ファイル システムのように blob の仮想階層をスキャンします。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As BlobListingDetails" />
      <MemberSignature Language="F#" Value="member this.Details : Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または応答に含めるデータの種類を示す一覧作成操作の詳細を設定します。
            </summary>
        <value>一覧作成操作に含める詳細。</value>
        <remarks>
            Include パラメーターは、応答は、次のサブセットの 1 つ以上含まれる必要がありますを指定します。 スナップショット、メタデータ、コミットされていない blob です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>