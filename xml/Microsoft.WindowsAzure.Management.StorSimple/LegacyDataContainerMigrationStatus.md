<Type Name="LegacyDataContainerMigrationStatus" FullName="Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus">
  <TypeSignature Language="C#" Value="public class LegacyDataContainerMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LegacyDataContainerMigrationStatus extends Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class LegacyDataContainerMigrationStatus&#xA;Inherits MigrationCommonModelFormatter" />
  <TypeSignature Language="F#" Value="type LegacyDataContainerMigrationStatus = class&#xA;    inherit MigrationCommonModelFormatter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0df52-101">1 つの特定の移行状態ですべてのデータ コンテナーの状態の移行</span><span class="sxs-lookup"><span data-stu-id="0df52-101">Status migration for all data containers in one particular Migration state</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LegacyDataContainerMigrationStatus (System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; overallStatusList, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; overallStatusList, valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus.#ctor(System.Collections.Generic.List{Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus},Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (overallStatusList As List(Of MigrationDataContainerStatus), type As MigrationStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus : System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus -&gt; Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus" Usage="new Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus (overallStatusList, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="overallStatusList" Type="System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt;" />
        <Parameter Name="type" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus" />
      </Parameters>
      <Docs>
        <param name="overallStatusList"><span data-ttu-id="0df52-102">移行の全体的な状態</span><span class="sxs-lookup"><span data-stu-id="0df52-102">overall migration status</span></span></param>
        <param name="type"><span data-ttu-id="0df52-103">MigrationStatus のリストの格納</span><span class="sxs-lookup"><span data-stu-id="0df52-103">MigrationStatus of the list of stored</span></span></param>
        <summary>
            <span data-ttu-id="0df52-104">構成体 LegacyDataContainerMigrationStatus オブジェクトのコンス トラクターは、全体的なステータス表示された一覧からフィルター処理で MigrationStatus を指定</span><span class="sxs-lookup"><span data-stu-id="0df52-104">Constructor - Constructs LegacyDataContainerMigrationStatus object of given MigrationStatus, by filtering from overall status list provided</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; StatusList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; StatusList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus.StatusList" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusList As List(Of MigrationDataContainerStatus)" />
      <MemberSignature Language="F#" Value="member this.StatusList : System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus.StatusList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0df52-105">特定の移行の状態で、ボリューム コンテナーの移行状態の一覧</span><span class="sxs-lookup"><span data-stu-id="0df52-105">List of migration status for the volume containers in the given migration state</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.LegacyDataContainerMigrationStatus.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="legacyDataContainerMigrationStatus.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0df52-106">移行の状態を目的の書式設定された文字列に変換します。</span><span class="sxs-lookup"><span data-stu-id="0df52-106">Converts migration status to the desired formatted string</span></span>
            </summary>
        <returns><span data-ttu-id="0df52-107">必要な形式で文字列としての移行の状態</span><span class="sxs-lookup"><span data-stu-id="0df52-107">Migration status as string in desired format</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>