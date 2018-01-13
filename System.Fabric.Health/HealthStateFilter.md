<Type Name="HealthStateFilter" FullName="System.Fabric.Health.HealthStateFilter">
  <TypeSignature Language="C#" Value="public enum HealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed HealthStateFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum HealthStateFilter" />
  <TypeSignature Language="F#" Value="type HealthStateFilter = " />
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
      <para>フィルターの型のパラメーターを列挙<see cref="T:System.Fabric.Health.HealthState" />です。 この列挙体には、<see cref="T:System.FlagsAttribute" />メンバー値のビットごとの組み合わせをできるようにします。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Health.HealthStateFilter All = int64(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthStateFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 65535" Usage="System.Fabric.Health.HealthStateFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
          <para>いずれかに一致するフィルター<see cref="T:System.Fabric.Health.HealthState" />です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Health.HealthStateFilter Default = int64(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthStateFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Health.HealthStateFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>既定値です。 使用状況、に応じて可能性がありますいずれにも一致<see cref="T:System.Fabric.Health.HealthState" />または none です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="Error" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Health.HealthStateFilter Error = int64(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthStateFilter.Error" />
      <MemberSignature Language="VB.NET" Value="Error" />
      <MemberSignature Language="F#" Value="Error = 8" Usage="System.Fabric.Health.HealthStateFilter.Error" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para>入力値と一致するフィルター<see cref="F:System.Fabric.Health.HealthState.Error" />です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Health.HealthStateFilter None = int64(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthStateFilter.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="System.Fabric.Health.HealthStateFilter.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>一致しないフィルター<see cref="T:System.Fabric.Health.HealthStateFilter" />です。 状態の特定のコレクションの結果が返されないようにするために使用されます。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Ok">
      <MemberSignature Language="C#" Value="Ok" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Health.HealthStateFilter Ok = int64(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthStateFilter.Ok" />
      <MemberSignature Language="VB.NET" Value="Ok" />
      <MemberSignature Language="F#" Value="Ok = 2" Usage="System.Fabric.Health.HealthStateFilter.Ok" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>入力値と一致するフィルター<see cref="F:System.Fabric.Health.HealthState.Ok" />です。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Warning">
      <MemberSignature Language="C#" Value="Warning" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Health.HealthStateFilter Warning = int64(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthStateFilter.Warning" />
      <MemberSignature Language="VB.NET" Value="Warning" />
      <MemberSignature Language="F#" Value="Warning = 4" Usage="System.Fabric.Health.HealthStateFilter.Warning" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>入力値と一致するフィルター<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>