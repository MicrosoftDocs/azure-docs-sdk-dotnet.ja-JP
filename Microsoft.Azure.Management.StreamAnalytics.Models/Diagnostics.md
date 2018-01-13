<Type Name="Diagnostics" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics">
  <TypeSignature Language="C#" Value="public class Diagnostics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Diagnostics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" />
  <TypeSignature Language="VB.NET" Value="Public Class Diagnostics" />
  <TypeSignature Language="F#" Value="type Diagnostics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            顧客のアテンションを正当化する、入力、出力、または、全体的なジョブに適用可能な条件について説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Diagnostics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            診断クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Diagnostics (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; conditions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; conditions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional conditions As IList(Of DiagnosticCondition) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics conditions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="conditions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt;" />
      </Parameters>
      <Docs>
        <param name="conditions">0 個以上の条件のリソース、またはに全体的に、ジョブに該当する顧客のアテンションを保証するコレクション。</param>
        <summary>
            診断クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Conditions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; Conditions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt; Conditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics.Conditions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Conditions As IList(Of DiagnosticCondition)" />
      <MemberSignature Language="F#" Value="member this.Conditions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Diagnostics.Conditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="conditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.DiagnosticCondition&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            0 個以上の条件のリソース、またはに全体的に、ジョブに該当する顧客のアテンションを保証するコレクションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>