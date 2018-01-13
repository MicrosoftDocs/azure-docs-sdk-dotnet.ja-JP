<Type Name="DiagnosticsProfile" FullName="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile">
  <TypeSignature Language="C#" Value="public class DiagnosticsProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticsProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticsProfile" />
  <TypeSignature Language="F#" Value="type DiagnosticsProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ブート診断設定の状態を指定します。
            &lt;ブラジル&gt;&lt;br&gt;最小 api バージョン: 2015-06-15 です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DiagnosticsProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsProfile (Microsoft.Azure.Management.Compute.Models.BootDiagnostics bootDiagnostics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.BootDiagnostics bootDiagnostics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile.#ctor(Microsoft.Azure.Management.Compute.Models.BootDiagnostics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.BootDiagnostics -&gt; Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" Usage="new Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile bootDiagnostics" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bootDiagnostics" Type="Microsoft.Azure.Management.Compute.Models.BootDiagnostics" />
      </Parameters>
      <Docs>
        <param name="bootDiagnostics">ブート診断は、デバッグ機能を VM の状態を診断するには、コンソール出力とスクリーン ショットを表示することができます。 &lt;ブラジル&gt;&lt;br&gt; Linux 仮想マシンのコンソールのログの出力に簡単に表示できます。
            &lt;ブラジル&gt;&lt;br&gt; Windows と Linux の両方の仮想マシンの Azure することもできます、ハイパーバイザーから仮想マシンのスクリーン ショットを参照してください。</param>
        <summary>
            DiagnosticsProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.BootDiagnostics BootDiagnostics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.BootDiagnostics BootDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile.BootDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public Property BootDiagnostics As BootDiagnostics" />
      <MemberSignature Language="F#" Value="member this.BootDiagnostics : Microsoft.Azure.Management.Compute.Models.BootDiagnostics with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile.BootDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bootDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.BootDiagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはブート診断は VM の状態を診断するには、コンソール出力とスクリーン ショットを表示することができますが、デバッグ機能を設定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Linux 仮想マシンのコンソールのログの出力に簡単に表示できます。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows と Linux の両方の仮想マシンの Azure することもできます、ハイパーバイザーから仮想マシンのスクリーン ショットを参照してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>