<Type Name="BackupOption" FullName="Microsoft.ServiceFabric.Data.BackupOption">
  <TypeSignature Language="C#" Value="public enum BackupOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed BackupOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum BackupOption" />
  <TypeSignature Language="F#" Value="type BackupOption = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="7d62f-101">バックアップの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="7d62f-101">Indicates the kind of the backup.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Full">
      <MemberSignature Language="C#" Value="Full" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.BackupOption Full = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.BackupOption.Full" />
      <MemberSignature Language="VB.NET" Value="Full" />
      <MemberSignature Language="F#" Value="Full = 0" Usage="Microsoft.ServiceFabric.Data.BackupOption.Full" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d62f-102">によって管理されるすべての状態の完全バックアップ、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />です。</span><span class="sxs-lookup"><span data-stu-id="7d62f-102">A full backup of all state managed by the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Incremental">
      <MemberSignature Language="C#" Value="Incremental" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.BackupOption Incremental = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.BackupOption.Incremental" />
      <MemberSignature Language="VB.NET" Value="Incremental" />
      <MemberSignature Language="F#" Value="Incremental = 1" Usage="Microsoft.ServiceFabric.Data.BackupOption.Incremental" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d62f-103">レプリカの増分バックアップです。</span><span class="sxs-lookup"><span data-stu-id="7d62f-103">Incremental backup of the replica.</span></span> <span data-ttu-id="7d62f-104">つまり、変更のみ最終フルまたは増分バックアップがバックアップされるためです。</span><span class="sxs-lookup"><span data-stu-id="7d62f-104">i.e. only the changes since the last full or incremental backup will be backed up.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>