<Type Name="SimpleWebSecurityToken" FullName="Microsoft.ServiceBus.SimpleWebSecurityToken">
  <TypeSignature Language="C#" Value="public class SimpleWebSecurityToken : System.IdentityModel.Tokens.SecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SimpleWebSecurityToken extends System.IdentityModel.Tokens.SecurityToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />
  <TypeSignature Language="VB.NET" Value="Public Class SimpleWebSecurityToken&#xA;Inherits SecurityToken" />
  <TypeSignature Language="F#" Value="type SimpleWebSecurityToken = class&#xA;    inherit SecurityToken" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IdentityModel.Tokens.SecurityToken</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Simple Web Token をラップするセキュリティ トークンです。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityToken.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityToken : string -&gt; Microsoft.ServiceBus.SimpleWebSecurityToken" Usage="new Microsoft.ServiceBus.SimpleWebSecurityToken tokenString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString">Simple Web Token を表す文字列。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />指定された Simple Web Token を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString, DateTime expiry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityToken.#ctor(System.String,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityToken : string * DateTime -&gt; Microsoft.ServiceBus.SimpleWebSecurityToken" Usage="new Microsoft.ServiceBus.SimpleWebSecurityToken (tokenString, expiry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="tokenString">Simple Web Token を表す文字列。</param>
        <param name="expiry">単純な web トークンの有効期限日です。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />指定 Simple Web Token や有効期限の日付を持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string id, string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityToken : string * string -&gt; Microsoft.ServiceBus.SimpleWebSecurityToken" Usage="new Microsoft.ServiceBus.SimpleWebSecurityToken (id, tokenString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">単純な Web トークンの一意の識別子。</param>
        <param name="tokenString">Simple Web Token を表す文字列。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" />トークン ID および Simple Web Token に指定したクラスです。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NullReferenceException"><paramref name="id" />パラメーターまたは<paramref name="tokenString" />パラメーターが null です。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString, DateTime expiry, string audience);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry, string audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.SimpleWebSecurityToken.#ctor(System.String,System.DateTime,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime, audience As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.SimpleWebSecurityToken : string * DateTime * string -&gt; Microsoft.ServiceBus.SimpleWebSecurityToken" Usage="new Microsoft.ServiceBus.SimpleWebSecurityToken (tokenString, expiry, audience)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
        <Parameter Name="audience" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString">Simple Web Token を表す文字列。</param>
        <param name="expiry">単純な web トークンの有効期限日です。</param>
        <param name="audience">単純な web トークンの対象ユーザーです。</param>
        <summary><see cref="T:Microsoft.ServiceBus.SimpleWebSecurityToken" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Audience">
      <MemberSignature Language="C#" Value="public string Audience { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Audience" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.Audience" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Audience As String" />
      <MemberSignature Language="F#" Value="member this.Audience : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.Audience" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>単純な web トークンの対象ユーザーを取得します。</summary>
        <value>単純な web トークンの対象ユーザーです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AudienceFieldName">
      <MemberSignature Language="C#" Value="protected virtual string AudienceFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AudienceFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.AudienceFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property AudienceFieldName As String" />
      <MemberSignature Language="F#" Value="member this.AudienceFieldName : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.AudienceFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>想定読者は、フィールド名を取得します。</summary>
        <value>対象のフィールド名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOn">
      <MemberSignature Language="C#" Value="public DateTime ExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.ExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresOn As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresOn : DateTime" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.ExpiresOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>セキュリティ トークンの有効期限が切れる日時を取得します。</summary>
        <value>日付と時間、セキュリティ トークンの有効期限が切れます。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOnFieldName">
      <MemberSignature Language="C#" Value="protected virtual string ExpiresOnFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpiresOnFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.ExpiresOnFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property ExpiresOnFieldName As String" />
      <MemberSignature Language="F#" Value="member this.ExpiresOnFieldName : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.ExpiresOnFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トークンの有効期限に関連付けられているフィールド名を取得します。</summary>
        <value>トークンの有効期限に関連付けられているフィールド名です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public override string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Simple Web Token に関連付けられている ID を取得します。</summary>
        <value>Simple Web Token に関連付けられている ID です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueSeparator">
      <MemberSignature Language="C#" Value="protected virtual string KeyValueSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyValueSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.KeyValueSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property KeyValueSeparator As String" />
      <MemberSignature Language="F#" Value="member this.KeyValueSeparator : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.KeyValueSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トークンに関連付けられているキーの値の区切り記号を取得します。</summary>
        <value>トークンに関連付けられているキーの値の区切り記号。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairSeparator">
      <MemberSignature Language="C#" Value="protected virtual string PairSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PairSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.PairSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property PairSeparator As String" />
      <MemberSignature Language="F#" Value="member this.PairSeparator : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.PairSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トークンに関連付けられている組の区切り記号を取得します。</summary>
        <value>トークンに関連付けられている組の区切り記号。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityKeys">
      <MemberSignature Language="C#" Value="public override System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt; SecurityKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.IdentityModel.Tokens.SecurityKey&gt; SecurityKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.SecurityKeys" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property SecurityKeys As ReadOnlyCollection(Of SecurityKey)" />
      <MemberSignature Language="F#" Value="member this.SecurityKeys : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt;" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.SecurityKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>セキュリティ トークンに関連付けられた暗号化キーを取得します。</summary>
        <value>A<see cref="T:System.Collections.ObjectModel.ReadOnlyCollection`1" />型の<see cref="T:System.IdentityModel.Tokens.SecurityKey" />Simple Web Token に関連付けられているキーのセットを格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.Token" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>単純な Web トークンを取得します。</summary>
        <value>単純な Web トークンです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidFrom">
      <MemberSignature Language="C#" Value="public override DateTime ValidFrom { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ValidFrom" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.ValidFrom" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property ValidFrom As DateTime" />
      <MemberSignature Language="F#" Value="member this.ValidFrom : DateTime" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.ValidFrom" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>実装されていません。 </summary>
        <value><see cref="T:System.NotImplementedException" /> をスローします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidTo">
      <MemberSignature Language="C#" Value="public override DateTime ValidTo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ValidTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.SimpleWebSecurityToken.ValidTo" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property ValidTo As DateTime" />
      <MemberSignature Language="F#" Value="member this.ValidTo : DateTime" Usage="Microsoft.ServiceBus.SimpleWebSecurityToken.ValidTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>実装されていません。</summary>
        <value><see cref="T:System.NotImplementedException" /> をスローします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>