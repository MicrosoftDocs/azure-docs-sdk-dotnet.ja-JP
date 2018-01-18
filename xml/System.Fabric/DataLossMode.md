<Type Name="DataLossMode" FullName="System.Fabric.DataLossMode">
  <TypeSignature Language="C#" Value="public enum DataLossMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed DataLossMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.DataLossMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum DataLossMode" />
  <TypeSignature Language="F#" Value="type DataLossMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="0d2c6-101">この列挙型は、データ消失テストの容易性データの損失を強制実行の種類を示すために API に渡されます。</span><span class="sxs-lookup"><span data-stu-id="0d2c6-101">This enum is passed to the DataLoss testability API to indicate what type of data loss to induce.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FullDataLoss">
      <MemberSignature Language="C#" Value="FullDataLoss" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.DataLossMode FullDataLoss = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.DataLossMode.FullDataLoss" />
      <MemberSignature Language="VB.NET" Value="FullDataLoss" />
      <MemberSignature Language="F#" Value="FullDataLoss = 2" Usage="System.Fabric.DataLossMode.FullDataLoss" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DataLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d2c6-102">FullDataLoss オプションには、すべてのデータが失われることを意味するすべてのレプリカが削除されます。</span><span class="sxs-lookup"><span data-stu-id="0d2c6-102">FullDataLoss option will drop all the replicas which means that all the data will be lost.</span></span> 
            </summary>
        <remarks>
            <span data-ttu-id="0d2c6-103">このオプションは、バックアップと回復のデータ パスをテストする場合に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="0d2c6-103">This option is very useful to test out backup and recovery data paths.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.DataLossMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.DataLossMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.DataLossMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DataLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d2c6-104">予約済み。</span><span class="sxs-lookup"><span data-stu-id="0d2c6-104">Reserved.</span></span>  <span data-ttu-id="0d2c6-105">API に渡すことはできません。</span><span class="sxs-lookup"><span data-stu-id="0d2c6-105">Do not pass into API.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PartialDataLoss">
      <MemberSignature Language="C#" Value="PartialDataLoss" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.DataLossMode PartialDataLoss = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.DataLossMode.PartialDataLoss" />
      <MemberSignature Language="VB.NET" Value="PartialDataLoss" />
      <MemberSignature Language="F#" Value="PartialDataLoss = 1" Usage="System.Fabric.DataLossMode.PartialDataLoss" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DataLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d2c6-106">PartialDataLoss オプションは、特定のパーティションのシステムで OnDataLoss イベントをトリガーする、停止するには、レプリカのクォーラムを引き起こすはします。</span><span class="sxs-lookup"><span data-stu-id="0d2c6-106">PartialDataLoss option will cause a quorum of replicas to go down, triggering an OnDataLoss event in the system for the given partition.</span></span> 
            </summary>
        <remarks>
            <span data-ttu-id="0d2c6-107">かどうかによって異なります実際のデータ損失が発生するかどうか、データ損失が発生しました時にまだレプリケートされているがコミットされたトランザクションが発生しました。</span><span class="sxs-lookup"><span data-stu-id="0d2c6-107">Whether actual data loss happens depends on whether there were committed transactions that were still being replicated at the time the data loss was induced</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>