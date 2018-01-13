<Type Name="OAuthBasedDataSourceProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties">
  <TypeSignature Language="C#" Value="public class OAuthBasedDataSourceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OAuthBasedDataSourceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class OAuthBasedDataSourceProperties" />
  <TypeSignature Language="F#" Value="type OAuthBasedDataSourceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            その認証モデルとして OAuth を使用するデータ ソースに関連付けられているプロパティです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OAuthBasedDataSourceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            OAuthBasedDataSourceProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OAuthBasedDataSourceProperties (string refreshToken = null, string tokenUserPrincipalName = null, string tokenUserDisplayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string refreshToken, string tokenUserPrincipalName, string tokenUserDisplayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional refreshToken As String = null, Optional tokenUserPrincipalName As String = null, Optional tokenUserDisplayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties : string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties (refreshToken, tokenUserPrincipalName, tokenUserDisplayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="refreshToken" Type="System.String" />
        <Parameter Name="tokenUserPrincipalName" Type="System.String" />
        <Parameter Name="tokenUserDisplayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="refreshToken">データ ソースに認証するために使用する有効なアクセス トークンの取得に使用できる更新トークンです。 有効な更新トークンは、現在、Azure ポータル経由で取得できのみです。 データ ソースと有効な更新トークンを使用してこのプロパティを更新する必要があるデータ ソースの認証に Azure ポータルに、継続を作成するときに、ダミーの文字列値をここに記述することをお勧めします。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="tokenUserPrincipalName">ユーザー プリンシパル名 (UPN)、更新トークンを取得するために使用されたユーザーのです。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</param>
        <param name="tokenUserDisplayName">更新トークンを取得するために使用されたユーザーのユーザーの表示名。 このプロパティを使用して、ヘルプのユーザーが更新トークンの取得に使用されたに注意してください。</param>
        <summary>
            OAuthBasedDataSourceProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="refreshToken")</AttributeName>
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
    <Member MemberName="TokenUserDisplayName">
      <MemberSignature Language="C#" Value="public string TokenUserDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserDisplayName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenUserDisplayName")</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenUserPrincipalName")</AttributeName>
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