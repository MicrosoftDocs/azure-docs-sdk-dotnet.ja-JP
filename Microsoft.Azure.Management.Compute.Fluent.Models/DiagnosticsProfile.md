<Type Name="DiagnosticsProfile" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile">
  <TypeSignature Language="C#" Value="public class DiagnosticsProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticsProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticsProfile" />
  <TypeSignature Language="F#" Value="type DiagnosticsProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            診断プロファイルをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticsProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public DiagnosticsProfile (Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics bootDiagnostics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics bootDiagnostics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile bootDiagnostics" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bootDiagnostics" Type="Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics" />
      </Parameters>
      <Docs>
        <param name="bootDiagnostics">ブート診断は、ユーザーがコンソール出力や、ハイパーバイザーから仮想マシンのスクリーン ショットを表示するデバッグ機能です。</param>
        <summary>
            DiagnosticsProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics BootDiagnostics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics BootDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile.BootDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public Property BootDiagnostics As BootDiagnostics" />
      <MemberSignature Language="F#" Value="member this.BootDiagnostics : Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile.BootDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bootDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.BootDiagnostics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはブート診断機能は、ハイパーバイザーからユーザーをコンソール出力の表示や、仮想マシンのスクリーン ショットを使用できるデバッグ機能を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>