<Type Name="TransactionIsolationLevel" FullName="System.Fabric.TransactionIsolationLevel">
  <TypeSignature Language="C#" Value="public enum TransactionIsolationLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TransactionIsolationLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TransactionIsolationLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum TransactionIsolationLevel" />
  <TypeSignature Language="F#" Value="type TransactionIsolationLevel = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>可能な分離レベルのセットを列挙、<see cref="T:System.Fabric.Transaction" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.TransactionIsolationLevel.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>ストアの既定の分離レベルを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReadCommitted">
      <MemberSignature Language="C#" Value="ReadCommitted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel ReadCommitted = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.ReadCommitted" />
      <MemberSignature Language="VB.NET" Value="ReadCommitted" />
      <MemberSignature Language="F#" Value="ReadCommitted = 2" Usage="System.Fabric.TransactionIsolationLevel.ReadCommitted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>揮発性のデータは、トランザクション中に読み取ることができませんが、変更できることを示します。 共有ロックがデータの読み取りをダーティ リードを回避するのには、反復不可能読み取りやファントム データになるトランザクションの終了前にデータを変更することができます。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReadUncommitted">
      <MemberSignature Language="C#" Value="ReadUncommitted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel ReadUncommitted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.ReadUncommitted" />
      <MemberSignature Language="VB.NET" Value="ReadUncommitted" />
      <MemberSignature Language="F#" Value="ReadUncommitted = 1" Usage="System.Fabric.TransactionIsolationLevel.ReadUncommitted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            トランザクション中に揮発性のデータを読み取ることを示します。 
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RepeatableRead">
      <MemberSignature Language="C#" Value="RepeatableRead" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel RepeatableRead = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.RepeatableRead" />
      <MemberSignature Language="VB.NET" Value="RepeatableRead" />
      <MemberSignature Language="F#" Value="RepeatableRead = 3" Usage="System.Fabric.TransactionIsolationLevel.RepeatableRead" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>揮発性データの読み取りが、トランザクション中に変更されないことを示します。 ロックは、その他のユーザーがデータを更新することを防止するクエリで使用されるすべてのデータに配置されます。 新しい行は、データ セットに挿入できるし、それ以降の読み取り、現在のトランザクションに含まれます。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Serializable">
      <MemberSignature Language="C#" Value="Serializable" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel Serializable = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.Serializable" />
      <MemberSignature Language="VB.NET" Value="Serializable" />
      <MemberSignature Language="F#" Value="Serializable = 5" Usage="System.Fabric.TransactionIsolationLevel.Serializable" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>揮発性のデータがシリアル化可能なことを示します。 揮発性のデータを読み取ることができますが、変更しないと、トランザクション中に新しいデータを追加することです。 データ セットでロックが配置される範囲を示します。 ロックでは、トランザクションが終了するまで更新またはデータ セットに挿入を防ぐためです。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="Snapshot" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TransactionIsolationLevel Snapshot = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TransactionIsolationLevel.Snapshot" />
      <MemberSignature Language="VB.NET" Value="Snapshot" />
      <MemberSignature Language="F#" Value="Snapshot = 4" Usage="System.Fabric.TransactionIsolationLevel.Snapshot" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>揮発性のデータを読み取ることができます、スナップショットのレベルを示します。 読み取られるデータには、トランザクションの開始時に存在していたデータのトランザクション一貫性のあるバージョンがあります。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>