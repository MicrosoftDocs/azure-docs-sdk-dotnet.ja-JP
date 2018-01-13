<Type Name="BackupEngineExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo">
  <TypeSignature Language="C#" Value="public class BackupEngineExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupEngineExtendedInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupEngineExtendedInfo" />
  <TypeSignature Language="F#" Value="type BackupEngineExtendedInfo = class" />
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
            その他のバックアップ エンジンについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupEngineExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            BackupEngineExtendedInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupEngineExtendedInfo (string databaseName = null, Nullable&lt;int&gt; protectedItemsCount = null, Nullable&lt;int&gt; protectedServersCount = null, Nullable&lt;int&gt; diskCount = null, Nullable&lt;double&gt; usedDiskSpace = null, Nullable&lt;double&gt; availableDiskSpace = null, Nullable&lt;DateTime&gt; refreshedAt = null, Nullable&lt;int&gt; azureProtectedInstances = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string databaseName, valuetype System.Nullable`1&lt;int32&gt; protectedItemsCount, valuetype System.Nullable`1&lt;int32&gt; protectedServersCount, valuetype System.Nullable`1&lt;int32&gt; diskCount, valuetype System.Nullable`1&lt;float64&gt; usedDiskSpace, valuetype System.Nullable`1&lt;float64&gt; availableDiskSpace, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; refreshedAt, valuetype System.Nullable`1&lt;int32&gt; azureProtectedInstances) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTime},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional databaseName As String = null, Optional protectedItemsCount As Nullable(Of Integer) = null, Optional protectedServersCount As Nullable(Of Integer) = null, Optional diskCount As Nullable(Of Integer) = null, Optional usedDiskSpace As Nullable(Of Double) = null, Optional availableDiskSpace As Nullable(Of Double) = null, Optional refreshedAt As Nullable(Of DateTime) = null, Optional azureProtectedInstances As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo (databaseName, protectedItemsCount, protectedServersCount, diskCount, usedDiskSpace, availableDiskSpace, refreshedAt, azureProtectedInstances)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="protectedItemsCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="protectedServersCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="diskCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="usedDiskSpace" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="availableDiskSpace" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="refreshedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="azureProtectedInstances" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="databaseName">バックアップ エンジンのデータベース名。</param>
        <param name="protectedItemsCount">バックアップ エンジンで保護された項目の数。</param>
        <param name="protectedServersCount">バックアップ エンジンで保護されたサーバーの数。</param>
        <param name="diskCount">バックアップ エンジン内のディスクの数です。</param>
        <param name="usedDiskSpace">バックアップ エンジンで使用されるディスク容量。</param>
        <param name="availableDiskSpace">バックアップ エンジンで現在使用できるディスク容量。</param>
        <param name="refreshedAt">最終バックアップ エンジンで時間を更新します。</param>
        <param name="azureProtectedInstances">バックアップ エンジンのインスタンスを保護します。</param>
        <summary>
            BackupEngineExtendedInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableDiskSpace">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AvailableDiskSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AvailableDiskSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.AvailableDiskSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableDiskSpace As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AvailableDiskSpace : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.AvailableDiskSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availableDiskSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンで現在使用できるディスク容量を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureProtectedInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AzureProtectedInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AzureProtectedInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.AzureProtectedInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureProtectedInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AzureProtectedInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.AzureProtectedInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureProtectedInstances")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンで保護されたインスタンスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンのデータベース名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.DiskCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.DiskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンでディスクの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemsCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProtectedItemsCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProtectedItemsCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.ProtectedItemsCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemsCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemsCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.ProtectedItemsCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedItemsCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンで保護された項目の数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedServersCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProtectedServersCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProtectedServersCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.ProtectedServersCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedServersCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProtectedServersCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.ProtectedServersCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedServersCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンで保護されたサーバーの数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RefreshedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RefreshedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.RefreshedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RefreshedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.RefreshedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="refreshedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンに最終更新時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsedDiskSpace">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; UsedDiskSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; UsedDiskSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.UsedDiskSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property UsedDiskSpace As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.UsedDiskSpace : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo.UsedDiskSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usedDiskSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバックアップ エンジンで使用されるディスク容量を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>