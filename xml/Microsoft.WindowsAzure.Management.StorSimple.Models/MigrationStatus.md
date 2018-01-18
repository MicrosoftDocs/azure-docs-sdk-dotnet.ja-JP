<Type Name="MigrationStatus" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus">
  <TypeSignature Language="C#" Value="public enum MigrationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MigrationStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum MigrationStatus" />
  <TypeSignature Language="F#" Value="type MigrationStatus = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="ee8d1-101">データ コンテナーの移行の状態を表します</span><span class="sxs-lookup"><span data-stu-id="ee8d1-101">Represents the migration status for a data container</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ee8d1-102">状態は、ボリューム コンテナーの移行が完了したことを示します</span><span class="sxs-lookup"><span data-stu-id="ee8d1-102">Status indicates the migration of volume container has completed</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus Failed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 2" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ee8d1-103">状態は、バックアップのボリューム コンテナーが失敗したことを示します</span><span class="sxs-lookup"><span data-stu-id="ee8d1-103">Status indicates the backup volume container has failed</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="InProgress">
      <MemberSignature Language="C#" Value="InProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus InProgress = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus.InProgress" />
      <MemberSignature Language="VB.NET" Value="InProgress" />
      <MemberSignature Language="F#" Value="InProgress = 1" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus.InProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ee8d1-104">ボリューム コンテナーの移行が進行中の状態を示します</span><span class="sxs-lookup"><span data-stu-id="ee8d1-104">Status indicates the migration of the volume container is in progress</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotStarted">
      <MemberSignature Language="C#" Value="NotStarted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus NotStarted = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus.NotStarted" />
      <MemberSignature Language="VB.NET" Value="NotStarted" />
      <MemberSignature Language="F#" Value="NotStarted = 0" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus.NotStarted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="ee8d1-105">状態は、ボリューム コンテナーの移行がまだ開始されていないことを示します</span><span class="sxs-lookup"><span data-stu-id="ee8d1-105">Status indicates the migration of the volume container has not yet started</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>