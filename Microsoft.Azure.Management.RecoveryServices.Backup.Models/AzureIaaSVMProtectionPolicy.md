<Type Name="AzureIaaSVMProtectionPolicy" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy">
  <TypeSignature Language="C#" Value="public class AzureIaaSVMProtectionPolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSVMProtectionPolicy extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSVMProtectionPolicy&#xA;Inherits ProtectionPolicy" />
  <TypeSignature Language="F#" Value="type AzureIaaSVMProtectionPolicy = class&#xA;    inherit ProtectionPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AzureIaasVM")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            IaaS VM ワークロードに固有のバックアップ ポリシー。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMProtectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AzureIaaSVMProtectionPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMProtectionPolicy (Nullable&lt;int&gt; protectedItemsCount = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy schedulePolicy = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy retentionPolicy = null, string timeZone = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; protectedItemsCount, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy schedulePolicy, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy retentionPolicy, string timeZone) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy.#ctor(System.Nullable{System.Int32},Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy,Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy : Nullable&lt;int&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy (protectedItemsCount, schedulePolicy, retentionPolicy, timeZone)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protectedItemsCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="schedulePolicy" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy" />
        <Parameter Name="timeZone" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protectedItemsCount">このポリシーに関連付けられている項目の数。</param>
        <param name="schedulePolicy">バックアップ スケジュールはバックアップ ポリシーの一部として指定します。</param>
        <param name="retentionPolicy">バックアップ保有期間の範囲についての詳細と保有ポリシーです。</param>
        <param name="timeZone">タイム ゾーンの省略可能な文字列として入力します。 例: タイム ゾーン「太平洋標準時」を = です。</param>
        <summary>
            AzureIaaSVMProtectionPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップの保有期間の範囲で詳細情報を保持ポリシーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulePolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy SchedulePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy SchedulePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy.SchedulePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulePolicy As SchedulePolicy" />
      <MemberSignature Language="F#" Value="member this.SchedulePolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy.SchedulePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedulePolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.SchedulePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ ポリシーの一部として指定されたバックアップ スケジュールを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectionPolicy.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または文字列としてタイム ゾーンの省略可能な入力を設定します。 例: タイム ゾーン「太平洋標準時」を = です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>