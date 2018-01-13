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
            バックアップの種類を示します。
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
            によって管理されるすべての状態の完全バックアップ、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />です。
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
            レプリカの増分バックアップです。 つまり、変更のみ最終フルまたは増分バックアップがバックアップされるためです。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>