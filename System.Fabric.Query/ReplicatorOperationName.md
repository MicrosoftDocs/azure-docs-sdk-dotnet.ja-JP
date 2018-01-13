<Type Name="ReplicatorOperationName" FullName="System.Fabric.Query.ReplicatorOperationName">
  <TypeSignature Language="C#" Value="public enum ReplicatorOperationName" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ReplicatorOperationName extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ReplicatorOperationName" />
  <TypeSignature Language="VB.NET" Value="Public Enum ReplicatorOperationName" />
  <TypeSignature Language="F#" Value="type ReplicatorOperationName = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>いずれかによって、レプリケーターによって現在実行中の操作を表す<see cref="T:System.Fabric.IReplicator" />または<see cref="T:System.Fabric.IPrimaryReplicator" />インターフェイスです。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="Abort" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Abort = int32(32)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Abort" />
      <MemberSignature Language="VB.NET" Value="Abort" />
      <MemberSignature Language="F#" Value="Abort = 32" Usage="System.Fabric.Query.ReplicatorOperationName.Abort" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>32</MemberValue>
      <Docs>
        <summary>
          <para>レプリケーターを中止しています。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Build">
      <MemberSignature Language="C#" Value="Build" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Build = int32(256)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Build" />
      <MemberSignature Language="VB.NET" Value="Build" />
      <MemberSignature Language="F#" Value="Build = 256" Usage="System.Fabric.Query.ReplicatorOperationName.Build" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>256</MemberValue>
      <Docs>
        <summary>
          <para>複製物作成会社では、1 つまたは複数のレプリカの作成中です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ChangeRole">
      <MemberSignature Language="C#" Value="ChangeRole" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName ChangeRole = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.ChangeRole" />
      <MemberSignature Language="VB.NET" Value="ChangeRole" />
      <MemberSignature Language="F#" Value="ChangeRole = 4" Usage="System.Fabric.Query.ReplicatorOperationName.ChangeRole" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>複製物作成会社は、そのロールを変更する処理を行っています。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Close">
      <MemberSignature Language="C#" Value="Close" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Close = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Close" />
      <MemberSignature Language="VB.NET" Value="Close" />
      <MemberSignature Language="F#" Value="Close = 16" Usage="System.Fabric.Query.ReplicatorOperationName.Close" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
          <para>レプリケーターを終了しています。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ReplicatorOperationName.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>レプリケーターがまだできていない場合は、既定値です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.Query.ReplicatorOperationName.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>複製物作成会社では、Service Fabric の観点からのすべての操作は実行されていません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="OnDataLoss">
      <MemberSignature Language="C#" Value="OnDataLoss" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName OnDataLoss = int32(64)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.OnDataLoss" />
      <MemberSignature Language="VB.NET" Value="OnDataLoss" />
      <MemberSignature Language="F#" Value="OnDataLoss = 64" Usage="System.Fabric.Query.ReplicatorOperationName.OnDataLoss" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>64</MemberValue>
      <Docs>
        <summary>
          <para>複製物作成会社は、ここで、ユーザーのサービス可能性があります可能性のある状態の回復、外部ソースからデータ損失の条件を処理です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="Open" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName Open = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.Open" />
      <MemberSignature Language="VB.NET" Value="Open" />
      <MemberSignature Language="F#" Value="Open = 2" Usage="System.Fabric.Query.ReplicatorOperationName.Open" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>レプリケーターは開いています。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpoch">
      <MemberSignature Language="C#" Value="UpdateEpoch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName UpdateEpoch = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.UpdateEpoch" />
      <MemberSignature Language="VB.NET" Value="UpdateEpoch" />
      <MemberSignature Language="F#" Value="UpdateEpoch = 8" Usage="System.Fabric.Query.ReplicatorOperationName.UpdateEpoch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para>レプリカ セットの変更、によってそのエポックで複製物作成会社を更新しています。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForCatchup">
      <MemberSignature Language="C#" Value="WaitForCatchup" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ReplicatorOperationName WaitForCatchup = int32(128)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ReplicatorOperationName.WaitForCatchup" />
      <MemberSignature Language="VB.NET" Value="WaitForCatchup" />
      <MemberSignature Language="F#" Value="WaitForCatchup = 128" Usage="System.Fabric.Query.ReplicatorOperationName.WaitForCatchup" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <MemberValue>128</MemberValue>
      <Docs>
        <summary>
          <para>レプリケーターを最新の状態キャッチするには、レプリカのクォーラムが待機しています。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>