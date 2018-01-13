<Type Name="SecurityProviderTpm" FullName="Microsoft.Azure.Devices.Shared.SecurityProviderTpm">
  <TypeSignature Language="C#" Value="public abstract class SecurityProviderTpm : Microsoft.Azure.Devices.Shared.SecurityProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SecurityProviderTpm extends Microsoft.Azure.Devices.Shared.SecurityProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Shared.SecurityProviderTpm" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SecurityProviderTpm&#xA;Inherits SecurityProvider" />
  <TypeSignature Language="F#" Value="type SecurityProviderTpm = class&#xA;    inherit SecurityProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Shared.SecurityProvider</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            TPM ハードウェア セキュリティ モジュール デバイスのセキュリティ プロバイダーのインターフェイスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityProviderTpm (string registrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (registrationId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Shared.SecurityProviderTpm : string -&gt; Microsoft.Azure.Devices.Shared.SecurityProviderTpm" Usage="new Microsoft.Azure.Devices.Shared.SecurityProviderTpm registrationId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId">このデバイスのプロビジョニング サービス登録 ID。</param>
        <summary>
            SecurityProviderTpm クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivateIdentityKey">
      <MemberSignature Language="C#" Value="public abstract void ActivateIdentityKey (byte[] encryptedKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ActivateIdentityKey(unsigned int8[] encryptedKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.ActivateIdentityKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub ActivateIdentityKey (encryptedKey As Byte())" />
      <MemberSignature Language="F#" Value="abstract member ActivateIdentityKey : byte[] -&gt; unit" Usage="securityProviderTpm.ActivateIdentityKey encryptedKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptedKey" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="encryptedKey">暗号化された id キー。</param>
        <summary>
            TPM デバイス内で id キーをアクティブにします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEndorsementKey">
      <MemberSignature Language="C#" Value="public abstract byte[] GetEndorsementKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] GetEndorsementKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.GetEndorsementKey" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetEndorsementKey () As Byte()" />
      <MemberSignature Language="F#" Value="abstract member GetEndorsementKey : unit -&gt; byte[]" Usage="securityProviderTpm.GetEndorsementKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            EndorsementKey を取得、Base64 にエンコードされます。
            </summary>
        <returns>EK を Base64 にエンコードされます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationID">
      <MemberSignature Language="C#" Value="public override string GetRegistrationID ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string GetRegistrationID() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.GetRegistrationID" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetRegistrationID () As String" />
      <MemberSignature Language="F#" Value="override this.GetRegistrationID : unit -&gt; string" Usage="securityProviderTpm.GetRegistrationID " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            デバイスの登録時に使用される登録 ID を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageRootKey">
      <MemberSignature Language="C#" Value="public abstract byte[] GetStorageRootKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] GetStorageRootKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.GetStorageRootKey" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetStorageRootKey () As Byte()" />
      <MemberSignature Language="F#" Value="abstract member GetStorageRootKey : unit -&gt; byte[]" Usage="securityProviderTpm.GetStorageRootKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            StorageRootKey を取得、Base64 にエンコードされます。
            </summary>
        <returns>SRK を Base64 にエンコードされます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sign">
      <MemberSignature Language="C#" Value="public abstract byte[] Sign (byte[] data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance unsigned int8[] Sign(unsigned int8[] data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Shared.SecurityProviderTpm.Sign(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Sign (data As Byte()) As Byte()" />
      <MemberSignature Language="F#" Value="abstract member Sign : byte[] -&gt; byte[]" Usage="securityProviderTpm.Sign data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Shared</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="data">署名する対象のデータ。</param>
        <summary>
            以前にアクティブ化された id キーを使用してデータに署名します。
            </summary>
        <returns>署名されるデータ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>