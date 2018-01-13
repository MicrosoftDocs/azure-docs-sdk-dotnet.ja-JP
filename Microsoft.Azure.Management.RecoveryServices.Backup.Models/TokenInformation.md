<Type Name="TokenInformation" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation">
  <TypeSignature Language="C#" Value="public class TokenInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TokenInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TokenInformation" />
  <TypeSignature Language="F#" Value="type TokenInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            トークンの情報の詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            TokenInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TokenInformation (string token = null, Nullable&lt;long&gt; expiryTimeInUtcTicks = null, string securityPIN = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string token, valuetype System.Nullable`1&lt;int64&gt; expiryTimeInUtcTicks, string securityPIN) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.#ctor(System.String,System.Nullable{System.Int64},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional token As String = null, Optional expiryTimeInUtcTicks As Nullable(Of Long) = null, Optional securityPIN As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation : string * Nullable&lt;int64&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation (token, expiryTimeInUtcTicks, securityPIN)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="expiryTimeInUtcTicks" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="securityPIN" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="token">トークンの値。</param>
        <param name="expiryTimeInUtcTicks">トークンの有効期限です。</param>
        <param name="securityPIN">セキュリティ暗証番号 (PIN)</param>
        <summary>
            TokenInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTimeInUtcTicks">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ExpiryTimeInUtcTicks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ExpiryTimeInUtcTicks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.ExpiryTimeInUtcTicks" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTimeInUtcTicks As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTimeInUtcTicks : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.ExpiryTimeInUtcTicks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expiryTimeInUtcTicks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンの有効期限を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityPIN">
      <MemberSignature Language="C#" Value="public string SecurityPIN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecurityPIN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.SecurityPIN" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityPIN As String" />
      <MemberSignature Language="F#" Value="member this.SecurityPIN : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.SecurityPIN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="securityPIN")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはセキュリティ PIN を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.TokenInformation.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="token")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンの値を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>