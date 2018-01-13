<Type Name="CloudStorageAccount" FullName="Microsoft.WindowsAzure.Storage.CloudStorageAccount">
  <TypeSignature Language="C#" Value="public sealed class CloudStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CloudStorageAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CloudStorageAccount" />
  <TypeSignature Language="F#" Value="type CloudStorageAccount = class" />
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
            Microsoft Azure ストレージ アカウントを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudStorageAccount (Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, bool useHttps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, bool useHttps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.#ctor(Microsoft.WindowsAzure.Storage.Auth.StorageCredentials,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.CloudStorageAccount : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials * bool -&gt; Microsoft.WindowsAzure.Storage.CloudStorageAccount" Usage="new Microsoft.WindowsAzure.Storage.CloudStorageAccount (storageCredentials, useHttps)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageCredentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
        <Parameter Name="useHttps" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="storageCredentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <param name="useHttps">
          <c>true</c>ストレージ サービスのエンドポイントへの接続に HTTPS を使用する場合は、 <c>false</c>です。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />クラスの指定された資格情報を使用して、ストレージ サービスへの接続に HTTP または HTTPS を使用するかどうかを指定します。 
            </summary>
        <remarks>ストレージ サービスへの接続に HTTPS を使用することをお勧めします。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudStorageAccount (Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, string endpointSuffix, bool useHttps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, string endpointSuffix, bool useHttps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.#ctor(Microsoft.WindowsAzure.Storage.Auth.StorageCredentials,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.CloudStorageAccount : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials * string * bool -&gt; Microsoft.WindowsAzure.Storage.CloudStorageAccount" Usage="new Microsoft.WindowsAzure.Storage.CloudStorageAccount (storageCredentials, endpointSuffix, useHttps)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageCredentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
        <Parameter Name="endpointSuffix" Type="System.String" />
        <Parameter Name="useHttps" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="storageCredentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <param name="endpointSuffix">"Core.windows.net"など、すべての記憶域サービスの DNS エンドポイントのサフィックスです。</param>
        <param name="useHttps">
          <c>true</c>ストレージ サービスのエンドポイントへの接続に HTTPS を使用する場合は、 <c>false</c>です。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />クラスの指定された資格情報とエンドポイントのサフィックスを使用して、ストレージ サービスへの接続に HTTP または HTTPS を使用するかどうかを指定します。
            </summary>
        <remarks>ストレージ サービスへの接続に HTTPS を使用することをお勧めします。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudStorageAccount (Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, string accountName, string endpointSuffix, bool useHttps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, string accountName, string endpointSuffix, bool useHttps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.#ctor(Microsoft.WindowsAzure.Storage.Auth.StorageCredentials,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.CloudStorageAccount : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials * string * string * bool -&gt; Microsoft.WindowsAzure.Storage.CloudStorageAccount" Usage="new Microsoft.WindowsAzure.Storage.CloudStorageAccount (storageCredentials, accountName, endpointSuffix, useHttps)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageCredentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="endpointSuffix" Type="System.String" />
        <Parameter Name="useHttps" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="storageCredentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <param name="accountName">アカウントの名前です。</param>
        <param name="endpointSuffix">"Core.windows.net"など、すべての記憶域サービスの DNS エンドポイントのサフィックスです。</param>
        <param name="useHttps">
          <c>true</c>ストレージ サービスのエンドポイントへの接続に HTTPS を使用する場合は、 <c>false</c>です。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />クラスの指定された資格情報とエンドポイントのサフィックスを使用して、ストレージ サービスへの接続に HTTP または HTTPS を使用するかどうかを指定します。
            </summary>
        <remarks>ストレージ サービスへの接続に HTTPS を使用することをお勧めします。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudStorageAccount (Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, Microsoft.WindowsAzure.Storage.StorageUri queueStorageUri, Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, Microsoft.WindowsAzure.Storage.StorageUri fileStorageUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, class Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, class Microsoft.WindowsAzure.Storage.StorageUri queueStorageUri, class Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, class Microsoft.WindowsAzure.Storage.StorageUri fileStorageUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.#ctor(Microsoft.WindowsAzure.Storage.Auth.StorageCredentials,Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.CloudStorageAccount : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials * Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri -&gt; Microsoft.WindowsAzure.Storage.CloudStorageAccount" Usage="new Microsoft.WindowsAzure.Storage.CloudStorageAccount (storageCredentials, blobStorageUri, queueStorageUri, tableStorageUri, fileStorageUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageCredentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
        <Parameter Name="blobStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="queueStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="tableStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="fileStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="storageCredentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <param name="blobStorageUri">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Blob サービスのエンドポイントまたはエンドポイントを指定します。</param>
        <param name="queueStorageUri">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Queue サービス エンドポイントまたはエンドポイントを指定します。</param>
        <param name="tableStorageUri">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Table サービス エンドポイントまたはエンドポイントを指定します。</param>
        <param name="fileStorageUri">A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />ファイル サービスのエンドポイントまたはエンドポイントを指定します。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />クラスの指定したアカウントの資格情報を使用して、サービス エンドポイント。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudStorageAccount (Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, Uri blobEndpoint, Uri queueEndpoint, Uri tableEndpoint, Uri fileEndpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials storageCredentials, class System.Uri blobEndpoint, class System.Uri queueEndpoint, class System.Uri tableEndpoint, class System.Uri fileEndpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.#ctor(Microsoft.WindowsAzure.Storage.Auth.StorageCredentials,System.Uri,System.Uri,System.Uri,System.Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.CloudStorageAccount : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials * Uri * Uri * Uri * Uri -&gt; Microsoft.WindowsAzure.Storage.CloudStorageAccount" Usage="new Microsoft.WindowsAzure.Storage.CloudStorageAccount (storageCredentials, blobEndpoint, queueEndpoint, tableEndpoint, fileEndpoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageCredentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
        <Parameter Name="blobEndpoint" Type="System.Uri" />
        <Parameter Name="queueEndpoint" Type="System.Uri" />
        <Parameter Name="tableEndpoint" Type="System.Uri" />
        <Parameter Name="fileEndpoint" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="storageCredentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <param name="blobEndpoint">A <see cref="T:System.Uri" /> Blob サービスのプライマリ エンドポイントを指定します。</param>
        <param name="queueEndpoint">A<see cref="T:System.Uri" />キュー サービスのプライマリ エンドポイントを指定します。</param>
        <param name="tableEndpoint">A<see cref="T:System.Uri" />テーブル サービスのプライマリ エンドポイントを指定します。</param>
        <param name="fileEndpoint">A<see cref="T:System.Uri" />ファイル サービスのプライマリ エンドポイントを指定します。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />クラスの指定された資格情報を使用して、サービス エンドポイント。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobEndpoint">
      <MemberSignature Language="C#" Value="public Uri BlobEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BlobEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.BlobEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.BlobEndpoint : Uri" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.BlobEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント用に構成された、Blob サービスのプライマリ エンドポイントを取得します。
            </summary>
        <value>A <see cref="T:System.Uri" /> Blob サービスのプライマリ エンドポイントを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobStorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri BlobStorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri BlobStorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.BlobStorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobStorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.BlobStorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.BlobStorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント用に構成されたに、プライマリとセカンダリの場所の Blob サービスのエンドポイントを取得します。
            </summary>
        <value>A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />の Blob サービス エンドポイントを表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCloudAnalyticsClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient CreateCloudAnalyticsClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient CreateCloudAnalyticsClient() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.CreateCloudAnalyticsClient" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCloudAnalyticsClient () As CloudAnalyticsClient" />
      <MemberSignature Language="F#" Value="member this.CreateCloudAnalyticsClient : unit -&gt; Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" Usage="cloudStorageAccount.CreateCloudAnalyticsClient " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            分析クライアントを作成します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCloudBlobClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient CreateCloudBlobClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient CreateCloudBlobClient() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.CreateCloudBlobClient" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCloudBlobClient () As CloudBlobClient" />
      <MemberSignature Language="F#" Value="member this.CreateCloudBlobClient : unit -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" Usage="cloudStorageAccount.CreateCloudBlobClient " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Blob サービス クライアントを作成します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCloudFileClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileClient CreateCloudFileClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.File.CloudFileClient CreateCloudFileClient() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.CreateCloudFileClient" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCloudFileClient () As CloudFileClient" />
      <MemberSignature Language="F#" Value="member this.CreateCloudFileClient : unit -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileClient" Usage="cloudStorageAccount.CreateCloudFileClient " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileClient</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ファイル サービス クライアントを作成します。
            </summary>
        <returns>ファイル サービスのエンドポイントを指定するクライアント オブジェクトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCloudQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient CreateCloudQueueClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient CreateCloudQueueClient() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.CreateCloudQueueClient" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCloudQueueClient () As CloudQueueClient" />
      <MemberSignature Language="F#" Value="member this.CreateCloudQueueClient : unit -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="cloudStorageAccount.CreateCloudQueueClient " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Queue サービス クライアントを作成します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCloudTableClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTableClient CreateCloudTableClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTableClient CreateCloudTableClient() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.CreateCloudTableClient" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCloudTableClient () As CloudTableClient" />
      <MemberSignature Language="F#" Value="member this.CreateCloudTableClient : unit -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="cloudStorageAccount.CreateCloudTableClient " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTableClient</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Table サービス クライアントを作成します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Auth.StorageCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            これを作成するために使用する資格情報を取得<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />オブジェクト。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DevelopmentStorageAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.CloudStorageAccount DevelopmentStorageAccount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.CloudStorageAccount DevelopmentStorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.DevelopmentStorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DevelopmentStorageAccount As CloudStorageAccount" />
      <MemberSignature Language="F#" Value="member this.DevelopmentStorageAccount : Microsoft.WindowsAzure.Storage.CloudStorageAccount" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.DevelopmentStorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.CloudStorageAccount</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />既知の開発ストレージ アカウントを参照するオブジェクト。
            </summary>
        <value>A<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />開発ストレージ アカウントを表すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileEndpoint">
      <MemberSignature Language="C#" Value="public Uri FileEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri FileEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.FileEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.FileEndpoint : Uri" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.FileEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント用に構成された、ファイル サービスのプライマリ エンドポイントを取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />ファイル サービスのプライマリ エンドポイントを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileStorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri FileStorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri FileStorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.FileStorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileStorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.FileStorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.FileStorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント用に構成されたに、プライマリとセカンダリの場所のファイル サービスのエンドポイントを取得します。
            </summary>
        <value>A<see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" />ファイル サービスのエンドポイントを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessAccountPolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy -&gt; string" Usage="cloudStorageAccount.GetSharedAccessSignature policy" />
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
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy" />
      </Parameters>
      <Docs>
        <param name="policy">A<see cref="T:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</param>
        <summary>
            アカウントの共有アクセス署名を返します。
            </summary>
        <returns>URI クエリ文字列としての共有アクセス署名します。</returns>
        <remarks>返されるクエリ文字列には、先頭に疑問符が含まれています。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parse">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.CloudStorageAccount Parse (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.CloudStorageAccount Parse(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.Parse(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Parse (connectionString As String) As CloudStorageAccount" />
      <MemberSignature Language="F#" Value="static member Parse : string -&gt; Microsoft.WindowsAzure.Storage.CloudStorageAccount" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.Parse connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.CloudStorageAccount</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">有効な接続文字列。</param>
        <summary>
            接続文字列を解析し、返します、<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />接続文字列から作成します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />接続文字列で指定された値から構築されたオブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">場合にスロー<paramref name="connectionString" />が null または空です。</exception>
        <exception cref="T:System.FormatException">場合にスロー<paramref name="connectionString" />は有効な接続文字列ではありません。</exception>
        <exception cref="T:System.ArgumentException">場合にスロー<paramref name="connectionString" />を解析できません。</exception>
      </Docs>
    </Member>
    <Member MemberName="QueueEndpoint">
      <MemberSignature Language="C#" Value="public Uri QueueEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri QueueEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.QueueEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.QueueEndpoint : Uri" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.QueueEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント用に構成された、キュー サービスのプライマリ エンドポイントを取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />キュー サービスのプライマリ エンドポイントを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueStorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri QueueStorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri QueueStorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.QueueStorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueStorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.QueueStorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.QueueStorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント用に構成されたに、プライマリとセカンダリの場所の Queue サービスのエンドポイントを取得します。
            </summary>
        <value>A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Queue サービスのエンドポイントを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableEndpoint">
      <MemberSignature Language="C#" Value="public Uri TableEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri TableEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.TableEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.TableEndpoint : Uri" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.TableEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント用に構成された、テーブル サービスのプライマリ エンドポイントを取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />テーブル サービスのプライマリ エンドポイントを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableStorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri TableStorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri TableStorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.TableStorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableStorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.TableStorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.TableStorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウント用に構成されたに、プライマリとセカンダリの場所のテーブル サービスのエンドポイントを取得します。
            </summary>
        <value>A <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Table サービスのエンドポイントを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="cloudStorageAccount.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            機密性の高いデータせず、このストレージ アカウント接続文字列を返します。
            </summary>
        <returns>接続文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public string ToString (bool exportSecrets);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ToString(bool exportSecrets) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.ToString(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToString (exportSecrets As Boolean) As String" />
      <MemberSignature Language="F#" Value="override this.ToString : bool -&gt; string" Usage="cloudStorageAccount.ToString exportSecrets" />
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
        <Parameter Name="exportSecrets" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportSecrets">
          <c>True</c>に機微なデータを文字列に含めるそれ以外の場合、 <c>false</c>です。</param>
        <summary>
            機密データを必要に応じて、ストレージ アカウントの接続文字列を返します。
            </summary>
        <returns>接続文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParse">
      <MemberSignature Language="C#" Value="public static bool TryParse (string connectionString, out Microsoft.WindowsAzure.Storage.CloudStorageAccount account);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryParse(string connectionString, [out] class Microsoft.WindowsAzure.Storage.CloudStorageAccount&amp; account) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.CloudStorageAccount.TryParse(System.String,Microsoft.WindowsAzure.Storage.CloudStorageAccount@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryParse (connectionString As String, ByRef account As CloudStorageAccount) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryParse : string *  -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.TryParse (connectionString, account)" />
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
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="account" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="connectionString">解析する接続文字列。</param>
        <param name="account">A<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />接続文字列を解析できるかどうかに返されるインスタンスを保持するオブジェクト。</param>
        <summary>
            返される接続文字列を解析できるかどうかを示す、<see cref="T:Microsoft.WindowsAzure.Storage.CloudStorageAccount" />オブジェクト。
            </summary>
        <returns>
          <b>true</b>接続文字列が正常に解析された、それ以外の場合は<b>false</b>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseV1MD5">
      <MemberSignature Language="C#" Value="public static bool UseV1MD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool UseV1MD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.CloudStorageAccount.UseV1MD5" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property UseV1MD5 As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseV1MD5 : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.CloudStorageAccount.UseV1MD5" />
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
            取得または FISMA MD5 設定を使用するかどうかを示す値を設定します。
            </summary>
        <value>
          <c>false</c> ; FISMA MD5 設定を使用するには<c>true</c> .NET の既定の実装を使用します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>