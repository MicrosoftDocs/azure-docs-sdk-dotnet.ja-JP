<Type Name="ServiceCorrelationScheme" FullName="System.Fabric.Description.ServiceCorrelationScheme">
  <TypeSignature Language="C#" Value="public enum ServiceCorrelationScheme" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceCorrelationScheme extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceCorrelationScheme" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceCorrelationScheme" />
  <TypeSignature Language="F#" Value="type ServiceCorrelationScheme = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>このサービスが別のサービスに関連付けられていて、そのサービスとの関係について説明することを示します。</para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Affinity">
      <MemberSignature Language="C#" Value="Affinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme Affinity = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.Affinity" />
      <MemberSignature Language="VB.NET" Value="Affinity" />
      <MemberSignature Language="F#" Value="Affinity = 1" Usage="System.Fabric.Description.ServiceCorrelationScheme.Affinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>このサービスが別のサービスとのアフィニティの関係を持つことを示します。 旧バージョンとの互換性のため、提供、Aligned または NonAlignedAffinity オプションを使い続ける理由を検討してください。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="AlignedAffinity">
      <MemberSignature Language="C#" Value="AlignedAffinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme AlignedAffinity = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.AlignedAffinity" />
      <MemberSignature Language="VB.NET" Value="AlignedAffinity" />
      <MemberSignature Language="F#" Value="AlignedAffinity = 2" Usage="System.Fabric.Description.ServiceCorrelationScheme.AlignedAffinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>アラインされたアフィニティによって、同じノードでアフィニティを設定したサービスのパーティションのプライマリが併置されています。 これは、既定値は、「アフィニティ」スキームを選択すると同じです。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.ServiceCorrelationScheme.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>無効な相関関係スキームの場合。 使用できません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NonAlignedAffinity">
      <MemberSignature Language="C#" Value="NonAlignedAffinity" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServiceCorrelationScheme NonAlignedAffinity = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServiceCorrelationScheme.NonAlignedAffinity" />
      <MemberSignature Language="VB.NET" Value="NonAlignedAffinity" />
      <MemberSignature Language="F#" Value="NonAlignedAffinity = 3" Usage="System.Fabric.Description.ServiceCorrelationScheme.NonAlignedAffinity" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceCorrelationScheme</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>非固定アフィニティでは、各サービスのすべてのレプリカが同じノード上に配置することを保証します。 配置のアフィニティとは異なりこれは保証されません特定のロールのレプリカを併置することです。 </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>