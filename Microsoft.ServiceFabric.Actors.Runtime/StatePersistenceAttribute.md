<Type Name="StatePersistenceAttribute" FullName="Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute">
  <TypeSignature Language="C#" Value="public sealed class StatePersistenceAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatePersistenceAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatePersistenceAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type StatePersistenceAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Class, Inherited=false)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            (メモリ内にのみ) が、永続化または格納されないすべてのアクターの状態を volatile にする必要があるかどうかを示します。
            この属性に指定されたストアの種類は、アクター サービスで使用される状態プロバイダーの種類に一致する必要があります。
            </summary>
    <remarks>
            StatePersistence 属性が派生クラスによって継承されない、各アクター型は、その StatePersistence を提供する必要がありますアクター型、StatePersistence 属性が指定されていない場合は、レベル アクターの状態がレプリケートされたかに書き込まれるディスクです。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatePersistenceAttribute (Microsoft.ServiceFabric.Actors.Runtime.StatePersistence statePersistence);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence statePersistence) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute.#ctor(Microsoft.ServiceFabric.Actors.Runtime.StatePersistence)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute : Microsoft.ServiceFabric.Actors.Runtime.StatePersistence -&gt; Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute" Usage="new Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute statePersistence" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="statePersistence" Type="Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" />
      </Parameters>
      <Docs>
        <param name="statePersistence">アクター サービス用のアクター状態の格納方法を示します。</param>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute" /> のインスタンスを作成します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatePersistence">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute.StatePersistence" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatePersistence As StatePersistence" />
      <MemberSignature Language="F#" Value="member this.StatePersistence : Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" Usage="Microsoft.ServiceFabric.Actors.Runtime.StatePersistenceAttribute.StatePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StatePersistence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の種類を表す列挙型にアクターは、使用するストアを状態します。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" />アクターに使用する状態ストアの種類を表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>