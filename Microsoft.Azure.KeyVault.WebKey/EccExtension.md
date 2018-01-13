<Type Name="EccExtension" FullName="Microsoft.Azure.KeyVault.WebKey.EccExtension">
  <TypeSignature Language="C#" Value="public static class EccExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed EccExtension extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.WebKey.EccExtension" />
  <TypeSignature Language="VB.NET" Value="Public Module EccExtension" />
  <TypeSignature Language="F#" Value="type EccExtension = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ECC の現在のバージョン サポートではない WebKey に必要な操作の一部であるために、これらの操作は、ECC 拡張として追加されます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExportParameters">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.KeyVault.WebKey.ECParameters ExportParameters (this System.Security.Cryptography.ECDsa ecdsa, bool includePrivateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.KeyVault.WebKey.ECParameters ExportParameters(class System.Security.Cryptography.ECDsa ecdsa, bool includePrivateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.EccExtension.ExportParameters(System.Security.Cryptography.ECDsa,System.Boolean)" />
      <MemberSignature Language="F#" Value="static member ExportParameters : System.Security.Cryptography.ECDsa * bool -&gt; Microsoft.Azure.KeyVault.WebKey.ECParameters" Usage="Microsoft.Azure.KeyVault.WebKey.EccExtension.ExportParameters (ecdsa, includePrivateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.ECParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ecdsa" Type="System.Security.Cryptography.ECDsa" RefType="this" />
        <Parameter Name="includePrivateParameters" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="ecdsa">任意のキーを使用して初期化 CNG オブジェクト</param>
        <param name="includePrivateParameters">秘密キー部分をエクスポートするかどうかを判断します。</param>
        <summary>
            CNG オブジェクトから EC パラメーターをエクスポートします。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyOperations">
      <MemberSignature Language="C#" Value="public static string[] GetKeyOperations (this System.Security.Cryptography.ECDsa ecdsa);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string[] GetKeyOperations(class System.Security.Cryptography.ECDsa ecdsa) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.EccExtension.GetKeyOperations(System.Security.Cryptography.ECDsa)" />
      <MemberSignature Language="F#" Value="static member GetKeyOperations : System.Security.Cryptography.ECDsa -&gt; string[]" Usage="Microsoft.Azure.KeyVault.WebKey.EccExtension.GetKeyOperations ecdsa" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ecdsa" Type="System.Security.Cryptography.ECDsa" RefType="this" />
      </Parameters>
      <Docs>
        <param name="ecdsa">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>