<Type Name="MigrationContainerConfirmStatus" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus">
  <TypeSignature Language="C#" Value="public class MigrationContainerConfirmStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationContainerConfirmStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationContainerConfirmStatus" />
  <TypeSignature Language="F#" Value="type MigrationContainerConfirmStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            このクラスを示す確認状態を特定のデータ コンテナーします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationContainerConfirmStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MigrationContainerConfirmStatus クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudConfigurationName">
      <MemberSignature Language="C#" Value="public string CloudConfigurationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CloudConfigurationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.CloudConfigurationName" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudConfigurationName As String" />
      <MemberSignature Language="F#" Value="member this.CloudConfigurationName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.CloudConfigurationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 取得または設定データ コンテナーの名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As MigrationOperation" />
      <MemberSignature Language="F#" Value="member this.Operation : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 取得または設定の確認が実行されている移行操作
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentageCompleted">
      <MemberSignature Language="C#" Value="public int PercentageCompleted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PercentageCompleted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.PercentageCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentageCompleted As Integer" />
      <MemberSignature Language="F#" Value="member this.PercentageCompleted : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.PercentageCompleted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 取得またはロールバック/コミット操作が完了した割合の設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerConfirmStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerConfirmStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As MigrationDataContainerConfirmStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerConfirmStatus with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerConfirmStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 取得または設定の確認の状態
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusMessage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo&gt; StatusMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo&gt; StatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.StatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusMessage As IList(Of HcsMessageInfo)" />
      <MemberSignature Language="F#" Value="member this.StatusMessage : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationContainerConfirmStatus.StatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必須。 ボリューム コンテナー レベルのメッセージと推奨事項を取得または設定が含まれています
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>