<Type Name="PartitionScheme" FullName="System.Fabric.Description.PartitionScheme">
  <TypeSignature Language="C#" Value="public enum PartitionScheme" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PartitionScheme extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PartitionScheme" />
  <TypeSignature Language="VB.NET" Value="Public Enum PartitionScheme" />
  <TypeSignature Language="F#" Value="type PartitionScheme = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>サービスがパーティション分割される方法を列挙します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.PartitionScheme Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.PartitionScheme.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.PartitionScheme.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>すべての Service Fabric の列挙は、「無効」の値を予約します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Named">
      <MemberSignature Language="C#" Value="Named" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.PartitionScheme Named = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.PartitionScheme.Named" />
      <MemberSignature Language="VB.NET" Value="Named" />
      <MemberSignature Language="F#" Value="Named = 3" Usage="System.Fabric.Description.PartitionScheme.Named" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>サービスがという名前のパーティション分割されていることを示します。 これは各パーティションは、文字列名に関連付けられていることを意味します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Singleton">
      <MemberSignature Language="C#" Value="Singleton" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.PartitionScheme Singleton = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.PartitionScheme.Singleton" />
      <MemberSignature Language="VB.NET" Value="Singleton" />
      <MemberSignature Language="F#" Value="Singleton = 1" Usage="System.Fabric.Description.PartitionScheme.Singleton" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>サービスがシングルトンのパーティション分割されていることを示します。 これは、1 つのパーティションがあること、またはサービスがパーティション分割されていないことを意味します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="UniformInt64Range">
      <MemberSignature Language="C#" Value="UniformInt64Range" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.PartitionScheme UniformInt64Range = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.PartitionScheme.UniformInt64Range" />
      <MemberSignature Language="VB.NET" Value="UniformInt64Range" />
      <MemberSignature Language="F#" Value="UniformInt64Range = 2" Usage="System.Fabric.Description.PartitionScheme.UniformInt64Range" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionScheme</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>サービスが uniform の int64 範囲パーティション分割されていることを示します。 これは、各パーティションが int64 キーの範囲を所有していることを意味します。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>