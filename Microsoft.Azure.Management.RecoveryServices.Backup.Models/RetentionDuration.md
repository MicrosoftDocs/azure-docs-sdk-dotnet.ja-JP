<Type Name="RetentionDuration" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration">
  <TypeSignature Language="C#" Value="public class RetentionDuration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RetentionDuration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration" />
  <TypeSignature Language="VB.NET" Value="Public Class RetentionDuration" />
  <TypeSignature Language="F#" Value="type RetentionDuration = class" />
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
            保有期間です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetentionDuration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RetentionDuration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetentionDuration (Nullable&lt;int&gt; count = null, string durationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; count, string durationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration.#ctor(System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional count As Nullable(Of Integer) = null, Optional durationType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration : Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration (count, durationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="durationType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="count">期間の種類の数。 保有期間は、カウント数がタイムアウト期間の種類によって取得されます。
            たとえば、ときにカウント = 3 および DurationType = 週、保有期間が 3 週間になります。</param>
        <param name="durationType">保有ポリシーの保有期間の種類です。 使用可能な値が含まれます: '無効'、'日'、'週数'、' 数か月'、'Years'</param>
        <summary>
            RetentionDuration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または継続時間の種類の数を設定します。 保有期間は、カウント数がタイムアウト期間の種類によって取得されます。
            たとえば、ときにカウント = 3 および DurationType = 週、保有期間が 3 週間になります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DurationType">
      <MemberSignature Language="C#" Value="public string DurationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DurationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration.DurationType" />
      <MemberSignature Language="VB.NET" Value="Public Property DurationType As String" />
      <MemberSignature Language="F#" Value="member this.DurationType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionDuration.DurationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="durationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または保持ポリシーの保有期間の種類を設定します。 使用可能な値が含まれます: '無効'、'日'、'週数'、' 数か月'、'Years'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>