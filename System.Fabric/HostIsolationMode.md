<Type Name="HostIsolationMode" FullName="System.Fabric.HostIsolationMode">
  <TypeSignature Language="C#" Value="public enum HostIsolationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed HostIsolationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.HostIsolationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum HostIsolationMode" />
  <TypeSignature Language="F#" Value="type HostIsolationMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            ホストの種類であるときに、コード パッケージのメイン エントリ ポイントの分離モードを示す<see cref="F:System.Fabric.HostType.ContainerHost" />です。 これは、操作は、サービス マニフェストのインポート中にコンテナー ホストでのポリシーのアプリケーション マニフェストの一部として指定します。
            </para>
      <remarks>
            ホスト入力以外の<see cref="F:System.Fabric.HostType.ContainerHost" />、その値は<see cref="F:System.Fabric.HostIsolationMode.None" />します。
            </remarks>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HyperV">
      <MemberSignature Language="C#" Value="HyperV" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode HyperV = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.HyperV" />
      <MemberSignature Language="VB.NET" Value="HyperV" />
      <MemberSignature Language="F#" Value="HyperV = 2" Usage="System.Fabric.HostIsolationMode.HyperV" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            示します、 <see cref="F:System.Fabric.HostType.ContainerHost" /> HYPER-V コンテナーです。
            これは、Windows コンテナーのみに適用されます。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="System.Fabric.HostIsolationMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>分離モードは指定されたことを示します<see cref="T:System.Fabric.HostType" />です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Process">
      <MemberSignature Language="C#" Value="Process" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.HostIsolationMode Process = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.HostIsolationMode.Process" />
      <MemberSignature Language="VB.NET" Value="Process" />
      <MemberSignature Language="F#" Value="Process = 1" Usage="System.Fabric.HostIsolationMode.Process" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>既定の分離モード、<see cref="F:System.Fabric.HostType.ContainerHost" />です。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>