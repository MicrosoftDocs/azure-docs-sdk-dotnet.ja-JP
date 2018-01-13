<Type Name="BEKDetails" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails">
  <TypeSignature Language="C#" Value="public class BEKDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BEKDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class BEKDetails" />
  <TypeSignature Language="F#" Value="type BEKDetails = class" />
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
            BEK は、bitlocker encrpytion キーです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BEKDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BEKDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BEKDetails (string secretUrl = null, string secretVaultId = null, string secretData = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string secretUrl, string secretVaultId, string secretData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional secretUrl As String = null, Optional secretVaultId As String = null, Optional secretData As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails (secretUrl, secretVaultId, secretData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secretUrl" Type="System.String" />
        <Parameter Name="secretVaultId" Type="System.String" />
        <Parameter Name="secretData" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="secretUrl">シークレットは、BEK です。</param>
        <param name="secretVaultId">このシークレットが格納されているキーの資格情報コンテナーの ID です。</param>
        <param name="secretData">BEK データ。</param>
        <summary>
            BEKDetails クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretData">
      <MemberSignature Language="C#" Value="public string SecretData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretData" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretData As String" />
      <MemberSignature Language="F#" Value="member this.SecretData : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または BEK データを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretUrl">
      <MemberSignature Language="C#" Value="public string SecretUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretUrl As String" />
      <MemberSignature Language="F#" Value="member this.SecretUrl : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定シークレットは BEK します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretVaultId">
      <MemberSignature Language="C#" Value="public string SecretVaultId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretVaultId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretVaultId" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretVaultId As String" />
      <MemberSignature Language="F#" Value="member this.SecretVaultId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BEKDetails.SecretVaultId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secretVaultId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのシークレットが格納されているキーの資格情報コンテナーの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>