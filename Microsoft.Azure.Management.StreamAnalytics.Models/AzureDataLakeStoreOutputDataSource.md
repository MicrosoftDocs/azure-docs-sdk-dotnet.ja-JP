<Type Name="AzureDataLakeStoreOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource">
  <TypeSignature Language="C#" Value="public class AzureDataLakeStoreOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureDataLakeStoreOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureDataLakeStoreOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type AzureDataLakeStoreOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.DataLake/Accounts")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Data Lake Store 出力のデータ ソースをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureDataLakeStoreOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreOutputDataSource (string refreshToken = null, string tokenUserPrincipalName = null, string tokenUserDisplayName = null, string accountName = null, string tenantId = null, string filePathPrefix = null, string dateFormat = null, string timeFormat = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string refreshToken, string tokenUserPrincipalName, string tokenUserDisplayName, string accountName, string tenantId, string filePathPrefix, string dateFormat, string timeFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional refreshToken As String = null, Optional tokenUserPrincipalName As String = null, Optional tokenUserDisplayName As String = null, Optional accountName As String = null, Optional tenantId As String = null, Optional filePathPrefix As String = null, Optional dateFormat As String = null, Optional timeFormat As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource (refreshToken, tokenUserPrincipalName, tokenUserDisplayName, accountName, tenantId, filePathPrefix, dateFormat, timeFormat)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="refreshToken" Type="System.String" />
        <Parameter Name="tokenUserPrincipalName" Type="System.String" />
        <Parameter Name="tokenUserDisplayName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="filePathPrefix" Type="System.String" />
        <Parameter Name="dateFormat" Type="System.String" />
        <Parameter Name="timeFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="refreshToken">データ ソースに認証するために使用する有効なアクセス トークンの取得に使用できる更新トークンです。 有効な更新トークンは、現在、Azure ポータル経由で取得できのみです。 データ ソースと有効な更新トークンを使用してこのプロパティを更新する必要があるデータ ソースの認証に Azure ポータルに、継続を作成するときに、ダミーの文字列値をここに記述することをお勧めします。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="tokenUserPrincipalName">ユーザー プリンシパル名 (UPN)、更新トークンを取得するために使用されたユーザーのです。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</param>
        <param name="tokenUserDisplayName">更新トークンを取得するために使用されたユーザーのユーザーの表示名。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</param>
        <param name="accountName">Azure Data Lake Store アカウントの名前。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="tenantId">更新トークンを取得するためのユーザーのテナント id です。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="filePathPrefix">出力に書き込むか、ファイルの場所です。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="dateFormat">日付形式です。 FilePathPrefix に {date} が表示されたら、場所にこのプロパティの値が代わりに日付形式として使用します。</param>
        <param name="timeFormat">時刻の形式。 FilePathPrefix に {date} が表示されたら、場所にこのプロパティの値が代わりに、時間形式として使用します。</param>
        <summary>
            AzureDataLakeStoreOutputDataSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Data Lake Store アカウントの名前を設定します。
            PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateFormat">
      <MemberSignature Language="C#" Value="public string DateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.DateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property DateFormat As String" />
      <MemberSignature Language="F#" Value="member this.DateFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.DateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または日付の書式を設定します。 FilePathPrefix に {date} が表示されたら、場所にこのプロパティの値が代わりに日付形式として使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePathPrefix">
      <MemberSignature Language="C#" Value="public string FilePathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.FilePathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.FilePathPrefix : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.FilePathPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filePathPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を出力に書き込むか、ファイルの場所。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータ ソースに認証するために使用する有効なアクセス トークンの取得に使用できる更新トークンを設定します。 有効な更新トークンは、現在、Azure ポータル経由で取得できのみです。 データ ソースと有効な更新トークンを使用してこのプロパティを更新する必要があるデータ ソースの認証に Azure ポータルに、継続を作成するときに、ダミーの文字列値をここに記述することをお勧めします。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または更新トークンを取得するために使用するユーザーのテナント id を設定します。 PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeFormat">
      <MemberSignature Language="C#" Value="public string TimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.TimeFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または時刻の形式を設定します。 FilePathPrefix に {date} が表示されたら、場所にこのプロパティの値が代わりに、時間形式として使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserDisplayName">
      <MemberSignature Language="C#" Value="public string TokenUserDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TokenUserDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserDisplayName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TokenUserDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenUserDisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または更新トークンを取得するために使用されたユーザーのユーザーの表示名を設定します。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserPrincipalName">
      <MemberSignature Language="C#" Value="public string TokenUserPrincipalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserPrincipalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TokenUserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureDataLakeStoreOutputDataSource.TokenUserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tokenUserPrincipalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または更新トークンを取得するために使用されたユーザーのユーザー プリンシパル名 (UPN) を設定します。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>