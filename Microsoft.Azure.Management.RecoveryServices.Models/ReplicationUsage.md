<Type Name="ReplicationUsage" FullName="Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage">
  <TypeSignature Language="C#" Value="public class ReplicationUsage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReplicationUsage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage" />
  <TypeSignature Language="VB.NET" Value="Public Class ReplicationUsage" />
  <TypeSignature Language="F#" Value="type ReplicationUsage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            資格情報コンテナーの使用状況を複製します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicationUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ReplicationUsage クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicationUsage (Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary monitoringSummary = null, Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary jobsSummary = null, Nullable&lt;int&gt; protectedItemCount = null, Nullable&lt;int&gt; recoveryPlanCount = null, Nullable&lt;int&gt; registeredServersCount = null, Nullable&lt;int&gt; recoveryServicesProviderAuthType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary monitoringSummary, class Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary jobsSummary, valuetype System.Nullable`1&lt;int32&gt; protectedItemCount, valuetype System.Nullable`1&lt;int32&gt; recoveryPlanCount, valuetype System.Nullable`1&lt;int32&gt; registeredServersCount, valuetype System.Nullable`1&lt;int32&gt; recoveryServicesProviderAuthType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.#ctor(Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary,Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage : Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary * Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage (monitoringSummary, jobsSummary, protectedItemCount, recoveryPlanCount, registeredServersCount, recoveryServicesProviderAuthType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="monitoringSummary" Type="Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary" />
        <Parameter Name="jobsSummary" Type="Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary" />
        <Parameter Name="protectedItemCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recoveryPlanCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="registeredServersCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recoveryServicesProviderAuthType" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="monitoringSummary">この資格情報コンテナーのデータの監視、レプリケーションの概要です。</param>
        <param name="jobsSummary">この資格情報コンテナーのレプリケーション ジョブのデータの概要です。</param>
        <param name="protectedItemCount">いくつかのレプリケーションには、この資格情報コンテナーの項目が保護されています。</param>
        <param name="recoveryPlanCount">この資格情報コンテナーのレプリケーションの復旧プランの数。</param>
        <param name="registeredServersCount">サーバーの数は、この資格情報コンテナーに登録します。</param>
        <param name="recoveryServicesProviderAuthType">資格情報コンテナーの復旧サービス プロバイダーの認証の種類。</param>
        <summary>
            ReplicationUsage クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobsSummary">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary JobsSummary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary JobsSummary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.JobsSummary" />
      <MemberSignature Language="VB.NET" Value="Public Property JobsSummary As JobsSummary" />
      <MemberSignature Language="F#" Value="member this.JobsSummary : Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.JobsSummary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobsSummary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.JobsSummary</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定がこの資格情報コンテナーのレプリケーション ジョブのデータの概要。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitoringSummary">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary MonitoringSummary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary MonitoringSummary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.MonitoringSummary" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitoringSummary As MonitoringSummary" />
      <MemberSignature Language="F#" Value="member this.MonitoringSummary : Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.MonitoringSummary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="monitoringSummary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Models.MonitoringSummary</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定がこの資格情報コンテナーのデータの監視、レプリケーションの概要。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProtectedItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProtectedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.ProtectedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.ProtectedItemCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedItemCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この資格情報コンテナーのレプリケーション保護された項目の数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPlanCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RecoveryPlanCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RecoveryPlanCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.RecoveryPlanCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPlanCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RecoveryPlanCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.RecoveryPlanCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPlanCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この資格情報コンテナーのレプリケーションの復旧プランの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryServicesProviderAuthType">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RecoveryServicesProviderAuthType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RecoveryServicesProviderAuthType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.RecoveryServicesProviderAuthType" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryServicesProviderAuthType As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RecoveryServicesProviderAuthType : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.RecoveryServicesProviderAuthType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryServicesProviderAuthType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または復旧サービス プロバイダーの認証の種類を資格情報コンテナーに設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredServersCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RegisteredServersCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RegisteredServersCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.RegisteredServersCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RegisteredServersCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RegisteredServersCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.ReplicationUsage.RegisteredServersCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="registeredServersCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この資格情報コンテナーに登録されたサーバーの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>