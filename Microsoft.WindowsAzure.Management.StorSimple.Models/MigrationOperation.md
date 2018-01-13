<Type Name="MigrationOperation" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation">
  <TypeSignature Language="C#" Value="public enum MigrationOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MigrationOperation extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation" />
  <TypeSignature Language="VB.NET" Value="Public Enum MigrationOperation" />
  <TypeSignature Language="F#" Value="type MigrationOperation = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            インポートされたボリューム コンテナーの操作が許可されていることを確認さまざまな移行操作を表します
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="Commit" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Commit = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Commit" />
      <MemberSignature Language="VB.NET" Value="Commit" />
      <MemberSignature Language="F#" Value="Commit = 1" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Commit" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            関連付けられているボリューム コンテナーをターゲット デバイスを完全にコミット
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            No 操作を表します
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Rollback">
      <MemberSignature Language="C#" Value="Rollback" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Rollback = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Rollback" />
      <MemberSignature Language="VB.NET" Value="Rollback" />
      <MemberSignature Language="F#" Value="Rollback = 2" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Rollback" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            ロールバックをクリーンアップ移行による変更とボリューム コンテナーの移行前の状態を元に戻します
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>