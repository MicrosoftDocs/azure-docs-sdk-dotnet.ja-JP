<Type Name="KeyAttributes" FullName="Microsoft.Azure.KeyVault.Models.KeyAttributes">
  <TypeSignature Language="C#" Value="public class KeyAttributes : Microsoft.Azure.KeyVault.Models.Attributes" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyAttributes extends Microsoft.Azure.KeyVault.Models.Attributes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeyAttributes" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyAttributes&#xA;Inherits Attributes" />
  <TypeSignature Language="F#" Value="type KeyAttributes = class&#xA;    inherit Attributes" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Models.Attributes</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Key vault サービスによって管理されるキーの属性です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyAttributes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyAttributes.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            KeyAttributes クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyAttributes (Nullable&lt;bool&gt; enabled = null, Nullable&lt;DateTime&gt; notBefore = null, Nullable&lt;DateTime&gt; expires = null, Nullable&lt;DateTime&gt; created = null, Nullable&lt;DateTime&gt; updated = null, string recoveryLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; notBefore, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expires, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updated, string recoveryLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyAttributes.#ctor(System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional notBefore As Nullable(Of DateTime) = null, Optional expires As Nullable(Of DateTime) = null, Optional created As Nullable(Of DateTime) = null, Optional updated As Nullable(Of DateTime) = null, Optional recoveryLevel As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyAttributes : Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.KeyVault.Models.KeyAttributes" Usage="new Microsoft.Azure.KeyVault.Models.KeyAttributes (enabled, notBefore, expires, created, updated, recoveryLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="notBefore" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expires" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updated" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryLevel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="enabled">オブジェクトが有効になっているかどうかを判断します。</param>
        <param name="notBefore">期間の開始時刻 (utc) 日付です。</param>
        <param name="expires">有効期限日 (utc)。</param>
        <param name="created">作成時刻 (utc) です。</param>
        <param name="updated">最終更新時刻 (utc)。</param>
        <param name="recoveryLevel">削除の回復のレベルは、現在有効で、現在の資格情報コンテナー内のキーが反映されます。 特権を持つユーザーは、キーを完全に削除 'Purgeable' が含まれている場合それ以外の場合、システムだけでは、保有期間の最後に、キーを削除できます。 使用可能な値が含まれます: 'パージ可能な'、' 回復可能な + Purgeable'、'回復可能な'、' 回復可能な + ProtectedSubscription'</param>
        <summary>
            KeyAttributes クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryLevel">
      <MemberSignature Language="C#" Value="public string RecoveryLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyAttributes.RecoveryLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecoveryLevel As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryLevel : string" Usage="Microsoft.Azure.KeyVault.Models.KeyAttributes.RecoveryLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得には、削除の回復のレベルは、現在有効で、現在の資格情報コンテナー内のキーが反映されます。 特権を持つユーザーは、キーを完全に削除 'Purgeable' が含まれている場合それ以外の場合、システムだけでは、保有期間の最後に、キーを削除できます。
            使用可能な値が含まれます: 'パージ可能な'、' 回復可能な + Purgeable'、'回復可能な'、' 回復可能な + ProtectedSubscription'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>