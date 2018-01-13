<Type Name="ConfigSplitHelper" FullName="Microsoft.WindowsAzure.Management.StorSimple.ConfigSplitHelper">
  <TypeSignature Language="C#" Value="public class ConfigSplitHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConfigSplitHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ConfigSplitHelper" />
  <TypeSignature Language="VB.NET" Value="Public Class ConfigSplitHelper" />
  <TypeSignature Language="F#" Value="type ConfigSplitHelper = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigSplitHelper ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ConfigSplitHelper.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Split">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig&gt; Split (Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig inputConfig);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig&gt; Split(class Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig inputConfig) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ConfigSplitHelper.Split(Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Split (inputConfig As LegacyApplianceConfig) As List(Of LegacyApplianceConfig)" />
      <MemberSignature Language="F#" Value="static member Split : Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig -&gt; System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.ConfigSplitHelper.Split inputConfig" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputConfig" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig" />
      </Parameters>
      <Docs>
        <param name="inputConfig">
            必須。 LegacyApplianceConfig の完全な一覧を解析
            </param>
        <summary>
            サービスを受け付けることができます、サイズの小さいチャンクで inputConfig を分割します。
            </summary>
        <returns>
            サービスが処理できる LegacyApplianceConfig の小さいチャンク
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>