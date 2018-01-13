<Type Name="ServicePartitionResolutionChange" FullName="System.Fabric.ServicePartitionResolutionChange">
  <TypeSignature Language="C#" Value="public sealed class ServicePartitionResolutionChange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePartitionResolutionChange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServicePartitionResolutionChange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePartitionResolutionChange" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolutionChange = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>このラッパーが含まれていますが、更新された<see cref="T:System.Fabric.ResolvedServicePartition" />です。 </para>
    </summary>
    <remarks>
      <para>新しいの中にスローされる例外が発生しました<see cref="T:System.Fabric.ResolvedServicePartition" />取得されると、次に、<see cref="T:System.Fabric.ServicePartitionResolutionChange" />も例外が含まれています。 されている場合、<see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" />プロパティが null でない、<see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" />プロパティが null です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="System.Fabric.ServicePartitionResolutionChange.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>関連するときにスローされた例外を取得<see cref="T:System.Fabric.ResolvedServicePartition" />取得中または更新されました。</para>
        </summary>
        <value>
          <para><see cref="T:System.Exception" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasException">
      <MemberSignature Language="C#" Value="public bool HasException { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasException" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.HasException" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasException As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasException : bool" Usage="System.Fabric.ServicePartitionResolutionChange.HasException" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>例外があったかどうかを示します。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
        </value>
        <remarks>
          <para>場合は、<see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" />パラメーターが null と<see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" />パラメーターを設定します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServicePartition Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServicePartition Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As ResolvedServicePartition" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.ResolvedServicePartition" Usage="System.Fabric.ServicePartitionResolutionChange.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>含む、新しい<see cref="T:System.Fabric.ResolvedServicePartition" />は登録されているサービスのパーティションに関連します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.ResolvedServicePartition" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>