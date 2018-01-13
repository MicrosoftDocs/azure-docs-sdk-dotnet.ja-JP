<Type Name="OAuthLinkedServiceBase" FullName="Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase">
  <TypeSignature Language="C#" Value="public abstract class OAuthLinkedServiceBase : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit OAuthLinkedServiceBase extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class OAuthLinkedServiceBase&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type OAuthLinkedServiceBase = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            OAuth の基本クラスには、サービスがリンクされています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OAuthLinkedServiceBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OAuthLinkedServiceBase (string authorization, string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string authorization, string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (authorization As String, sessionId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" Usage="new Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase (authorization, sessionId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authorization" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorization">To be added.</param>
        <param name="sessionId">To be added.</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase" />必須の引数を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public string Authorization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public Property Authorization As String" />
      <MemberSignature Language="F#" Value="member this.Authorization : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            あなたに代わってリソースにアクセスする ADF で使用する OAuth 承認します。 各認証には一意を一度だけ使用することがあります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OAuthLinkedServiceBase.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            OAuth 承認セッションからの OAuth セッション ID です。
            各セッション ID は一意と 1 回のみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>