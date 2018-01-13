<Type Name="SimpleWebSecurityTokenSerializer" FullName="Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer">
  <TypeSignature Language="C#" Value="public class SimpleWebSecurityTokenSerializer : System.IdentityModel.Selectors.SecurityTokenSerializer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SimpleWebSecurityTokenSerializer extends System.IdentityModel.Selectors.SecurityTokenSerializer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer" />
  <TypeSignature Language="VB.NET" Value="Public Class SimpleWebSecurityTokenSerializer&#xA;Inherits SecurityTokenSerializer" />
  <TypeSignature Language="F#" Value="type SimpleWebSecurityTokenSerializer = class&#xA;    inherit SecurityTokenSerializer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IdentityModel.Selectors.SecurityTokenSerializer</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>読み取りおよび書き込みを使用するクラスを表します<see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" />、 <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />、および<see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />オブジェクトを XML として。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityTokenSerializer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityTokenSerializer (System.IdentityModel.Selectors.SecurityTokenSerializer innerSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IdentityModel.Selectors.SecurityTokenSerializer innerSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.#ctor(System.IdentityModel.Selectors.SecurityTokenSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerSerializer As SecurityTokenSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer : System.IdentityModel.Selectors.SecurityTokenSerializer -&gt; Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer" Usage="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer innerSerializer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerSerializer" Type="System.IdentityModel.Selectors.SecurityTokenSerializer" />
      </Parameters>
      <Docs>
        <param name="innerSerializer">内部のシリアライザーとして使用するセキュリティ トークン シリアライザー。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer" />指定したセキュリティ トークン シリアライザーを持つクラス。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><paramref name="innerSerializer" /> パラメーターが null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="CanReadKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadKeyIdentifierClauseCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadKeyIdentifierClauseCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.CanReadKeyIdentifierClauseCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadKeyIdentifierClauseCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadKeyIdentifierClauseCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadKeyIdentifierClauseCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">キー識別句を読み取る <see cref="T:System.Xml.XmlReader" />。</param>
        <summary>このシリアライザ-が読み取ることができるかどうかを判断、 &lt;KeyIdentifier&gt;要素が指定した XML リーダーで参照します。</summary>
        <returns>true が指定された&lt;KeyIdentifier&gt;要素を読み取り、それ以外の場合は false にすることができます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReadKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadKeyIdentifierCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadKeyIdentifierCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.CanReadKeyIdentifierCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadKeyIdentifierCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadKeyIdentifierCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadKeyIdentifierCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">キー識別子を読み取る <see cref="T:System.Xml.XmlReader" />。</param>
        <summary>このシリアライザ-が読み取ることができるかどうかを判断、 &lt;KeyIdentifier&gt;要素が指定した XML リーダーで参照します。</summary>
        <returns>true が指定された&lt;KeyIdentifier&gt;要素を読み取り、それ以外の場合は false にすることができます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReadTokenCore">
      <MemberSignature Language="C#" Value="protected override bool CanReadTokenCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanReadTokenCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.CanReadTokenCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanReadTokenCore (reader As XmlReader) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanReadTokenCore : System.Xml.XmlReader -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanReadTokenCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">セキュリティ トークンを読み取る <see cref="T:System.Xml.XmlReader" />。</param>
        <summary>このシリアライザーが指定された XML リーダーで参照されているセキュリティ トークンを読み取ることができるかどうかを判断します。</summary>
        <returns>true のとき、セキュリティ トークンを読み取ることができます。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteKeyIdentifierClauseCore (System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteKeyIdentifierClauseCore(class System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.CanWriteKeyIdentifierClauseCore(System.IdentityModel.Tokens.SecurityKeyIdentifierClause)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteKeyIdentifierClauseCore (keyIdentifierClause As SecurityKeyIdentifierClause) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteKeyIdentifierClauseCore : System.IdentityModel.Tokens.SecurityKeyIdentifierClause -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteKeyIdentifierClauseCore keyIdentifierClause" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyIdentifierClause" Type="System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />
      </Parameters>
      <Docs>
        <param name="keyIdentifierClause">書き込むキー識別句を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />。</param>
        <summary>このシリアライザーが指定のキー識別句を書き込むことができるかどうかを判断します。</summary>
        <returns>このシリアライザーが指定したキー識別子句を書き込む場合は trueそれ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteKeyIdentifierCore (System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteKeyIdentifierCore(class System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.CanWriteKeyIdentifierCore(System.IdentityModel.Tokens.SecurityKeyIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteKeyIdentifierCore (keyIdentifier As SecurityKeyIdentifier) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteKeyIdentifierCore : System.IdentityModel.Tokens.SecurityKeyIdentifier -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteKeyIdentifierCore keyIdentifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyIdentifier" Type="System.IdentityModel.Tokens.SecurityKeyIdentifier" />
      </Parameters>
      <Docs>
        <param name="keyIdentifier">書き込むキーの ID を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />。</param>
        <summary>このシリアライザーが指定のキー ID を書き込むことができるかどうかを判断します。</summary>
        <returns>このシリアライザーが指定したキー識別子を書き込む場合は trueそれ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanWriteTokenCore">
      <MemberSignature Language="C#" Value="protected override bool CanWriteTokenCore (System.IdentityModel.Tokens.SecurityToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool CanWriteTokenCore(class System.IdentityModel.Tokens.SecurityToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.CanWriteTokenCore(System.IdentityModel.Tokens.SecurityToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CanWriteTokenCore (token As SecurityToken) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanWriteTokenCore : System.IdentityModel.Tokens.SecurityToken -&gt; bool" Usage="simpleWebSecurityTokenSerializer.CanWriteTokenCore token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.IdentityModel.Tokens.SecurityToken" />
      </Parameters>
      <Docs>
        <param name="token">XML に変換する <see cref="T:System.IdentityModel.Tokens.SecurityToken" />。</param>
        <summary>このシリアライザーが指定のセキュリティ トークンを XML に書き込むことができるかどうかを判断します。</summary>
        <returns>セキュリティ トークンを書き込むことができます。 場合は trueそれ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultInstance">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer DefaultInstance;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer DefaultInstance" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.DefaultInstance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultInstance As SimpleWebSecurityTokenSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultInstance : Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.DefaultInstance" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>インスタンスを指定します、<see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer" />クラスです。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityKeyIdentifierClause ReadKeyIdentifierClauseCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityKeyIdentifierClause ReadKeyIdentifierClauseCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.ReadKeyIdentifierClauseCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadKeyIdentifierClauseCore (reader As XmlReader) As SecurityKeyIdentifierClause" />
      <MemberSignature Language="F#" Value="override this.ReadKeyIdentifierClauseCore : System.Xml.XmlReader -&gt; System.IdentityModel.Tokens.SecurityKeyIdentifierClause" Usage="simpleWebSecurityTokenSerializer.ReadKeyIdentifierClauseCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityKeyIdentifierClause</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">キー識別句を読み取る <see cref="T:System.Xml.XmlReader" />。</param>
        <summary>指定した XML リーダーを使用してキー識別子句を読み取ります。</summary>
        <returns>読み取るキーの ID を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityKeyIdentifier ReadKeyIdentifierCore (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityKeyIdentifier ReadKeyIdentifierCore(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.ReadKeyIdentifierCore(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadKeyIdentifierCore (reader As XmlReader) As SecurityKeyIdentifier" />
      <MemberSignature Language="F#" Value="override this.ReadKeyIdentifierCore : System.Xml.XmlReader -&gt; System.IdentityModel.Tokens.SecurityKeyIdentifier" Usage="simpleWebSecurityTokenSerializer.ReadKeyIdentifierCore reader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityKeyIdentifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">キー識別子を読み取る <see cref="T:System.Xml.XmlReader" />。</param>
        <summary>指定した XML リーダーを使用してキー識別子を読み取ります。</summary>
        <returns>読み取るキーの ID を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTokenCore">
      <MemberSignature Language="C#" Value="protected override System.IdentityModel.Tokens.SecurityToken ReadTokenCore (System.Xml.XmlReader reader, System.IdentityModel.Selectors.SecurityTokenResolver tokenResolver);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IdentityModel.Tokens.SecurityToken ReadTokenCore(class System.Xml.XmlReader reader, class System.IdentityModel.Selectors.SecurityTokenResolver tokenResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.ReadTokenCore(System.Xml.XmlReader,System.IdentityModel.Selectors.SecurityTokenResolver)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ReadTokenCore (reader As XmlReader, tokenResolver As SecurityTokenResolver) As SecurityToken" />
      <MemberSignature Language="F#" Value="override this.ReadTokenCore : System.Xml.XmlReader * System.IdentityModel.Selectors.SecurityTokenResolver -&gt; System.IdentityModel.Tokens.SecurityToken" Usage="simpleWebSecurityTokenSerializer.ReadTokenCore (reader, tokenResolver)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IdentityModel.Tokens.SecurityToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
        <Parameter Name="tokenResolver" Type="System.IdentityModel.Selectors.SecurityTokenResolver" />
      </Parameters>
      <Docs>
        <param name="reader"><see cref="T:System.Xml.XmlReader" /> SimpleWebSecurityToken またはセキュリティ トークンを読み取る。</param>
        <param name="tokenResolver">セキュリティ トークンの種類を指定する <see cref="T:System.IdentityModel.Selectors.SecurityTokenResolver" />。</param>
        <summary>読み取り、<see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" />セキュリティ トークンが指定された XML リーダーで参照されているか。</summary>
        <returns>A <see cref="T:System.IdentityModel.Tokens.SecurityToken" /> SimpleWebSecurityToken または読み取られたセキュリティ トークンを表すです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException">XML 要素のエンコードは、base64Binary ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="WriteKeyIdentifierClauseCore">
      <MemberSignature Language="C#" Value="protected override void WriteKeyIdentifierClauseCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteKeyIdentifierClauseCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityKeyIdentifierClause keyIdentifierClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.WriteKeyIdentifierClauseCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityKeyIdentifierClause)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteKeyIdentifierClauseCore (writer As XmlWriter, keyIdentifierClause As SecurityKeyIdentifierClause)" />
      <MemberSignature Language="F#" Value="override this.WriteKeyIdentifierClauseCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityKeyIdentifierClause -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteKeyIdentifierClauseCore (writer, keyIdentifierClause)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="keyIdentifierClause" Type="System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />
      </Parameters>
      <Docs>
        <param name="writer"><see cref="T:System.Xml.XmlWriter" />キー識別子句を書き込むために使用します。</param>
        <param name="keyIdentifierClause">書き込むキー識別句を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifierClause" />。</param>
        <summary>指定された XML ライターを使用して、指定されたキー識別句を書き込みます。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteKeyIdentifierCore">
      <MemberSignature Language="C#" Value="protected override void WriteKeyIdentifierCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteKeyIdentifierCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityKeyIdentifier keyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.WriteKeyIdentifierCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityKeyIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteKeyIdentifierCore (writer As XmlWriter, keyIdentifier As SecurityKeyIdentifier)" />
      <MemberSignature Language="F#" Value="override this.WriteKeyIdentifierCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityKeyIdentifier -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteKeyIdentifierCore (writer, keyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="keyIdentifier" Type="System.IdentityModel.Tokens.SecurityKeyIdentifier" />
      </Parameters>
      <Docs>
        <param name="writer"><see cref="T:System.Xml.XmlWriter" />キー識別子を書き込むために使用します。</param>
        <param name="keyIdentifier">書き込むキーの ID を表す <see cref="T:System.IdentityModel.Tokens.SecurityKeyIdentifier" />。</param>
        <summary>指定された XML ライターを使用して、指定されたキー識別子を書き込みます。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">バイナリのトークンの内容が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="WriteTokenCore">
      <MemberSignature Language="C#" Value="protected override void WriteTokenCore (System.Xml.XmlWriter writer, System.IdentityModel.Tokens.SecurityToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void WriteTokenCore(class System.Xml.XmlWriter writer, class System.IdentityModel.Tokens.SecurityToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityTokenSerializer.WriteTokenCore(System.Xml.XmlWriter,System.IdentityModel.Tokens.SecurityToken)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub WriteTokenCore (writer As XmlWriter, token As SecurityToken)" />
      <MemberSignature Language="F#" Value="override this.WriteTokenCore : System.Xml.XmlWriter * System.IdentityModel.Tokens.SecurityToken -&gt; unit" Usage="simpleWebSecurityTokenSerializer.WriteTokenCore (writer, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
        <Parameter Name="token" Type="System.IdentityModel.Tokens.SecurityToken" />
      </Parameters>
      <Docs>
        <param name="writer"><see cref="T:System.Xml.XmlWriter" /> SimpleWebSecurityToken またはセキュリティの書き込みに使用されるトークン。</param>
        <param name="token">SimpleWebSecurityToken またはセキュリティを記述するトークンします。</param>
        <summary>指定した書き込み<see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" />または指定した XML ライターを使用してセキュリティ トークン。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>