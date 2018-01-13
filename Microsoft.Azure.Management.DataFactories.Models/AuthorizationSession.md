<Type Name="AuthorizationSession" FullName="Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession">
  <TypeSignature Language="C#" Value="public class AuthorizationSession" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthorizationSession extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthorizationSession" />
  <TypeSignature Language="F#" Value="type AuthorizationSession = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            OAuth 認証セッションを使用して、リソースにアクセスする、あなたに代わって ADF を許可する認証コード付与フローを開始します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AuthorizationSession クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationSession (Uri endpoint, string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpoint, string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As Uri, sessionId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession : Uri * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession" Usage="new Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession (endpoint, sessionId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint">To be added.</param>
        <param name="sessionId">To be added.</param>
        <summary>
            必須の引数で AuthorizationSession クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 OAuth 承認エンドポイントを使用して、ログイン情報とリソースにアクセスする、あなたに代わって ADF で使用できるが承認を取得します。 各認証には一意を一度だけ使用することがあります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 リンクされたサービスを OAuth を作成するときに、この値を提供します。
            各セッション ID は一意であり、1 回のみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>