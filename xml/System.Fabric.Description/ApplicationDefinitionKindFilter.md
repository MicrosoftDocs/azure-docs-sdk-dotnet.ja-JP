<Type Name="ApplicationDefinitionKindFilter" FullName="System.Fabric.Description.ApplicationDefinitionKindFilter">
  <TypeSignature Language="C#" Value="public enum ApplicationDefinitionKindFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ApplicationDefinitionKindFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationDefinitionKindFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum ApplicationDefinitionKindFilter" />
  <TypeSignature Language="F#" Value="type ApplicationDefinitionKindFilter = " />
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
      <para><span data-ttu-id="8c629-101">クエリによって返されるアプリケーションの定義の種類の照合に使用されるフィルターを列挙します。</span><span class="sxs-lookup"><span data-stu-id="8c629-101">Enumerates the filters used for matching the definition kind of applications that should be returned by query.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="8c629-102">この列挙体には、<see cref="T:System.FlagsAttribute" />そのメンバーのビットごとの組み合わせをできるようにします。</span><span class="sxs-lookup"><span data-stu-id="8c629-102">This enumeration has a <see cref="T:System.FlagsAttribute" /> that allows a bitwise combination of its members.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationDefinitionKindFilter All = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDefinitionKindFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 65535" Usage="System.Fabric.Description.ApplicationDefinitionKindFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8c629-103">定義の種類のフィルターは追加されませんを示します。</span><span class="sxs-lookup"><span data-stu-id="8c629-103">Indicates no filter is added on definition kind.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Compose">
      <MemberSignature Language="C#" Value="Compose" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationDefinitionKindFilter Compose = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDefinitionKindFilter.Compose" />
      <MemberSignature Language="VB.NET" Value="Compose" />
      <MemberSignature Language="F#" Value="Compose = 2" Usage="System.Fabric.Description.ApplicationDefinitionKindFilter.Compose" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8c629-104">定義されている一致するアプリケーションがファイルを作成するフィルターを示します。</span><span class="sxs-lookup"><span data-stu-id="8c629-104">Indicates a filter that matches applications defined by compose file(s).</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationDefinitionKindFilter Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDefinitionKindFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Description.ApplicationDefinitionKindFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8c629-105">定義の種類のフィルターは追加されませんを示します。</span><span class="sxs-lookup"><span data-stu-id="8c629-105">Indicates no filter is added on definition kind.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ServiceFabricApplicationDescription">
      <MemberSignature Language="C#" Value="ServiceFabricApplicationDescription" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationDefinitionKindFilter ServiceFabricApplicationDescription = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDefinitionKindFilter.ServiceFabricApplicationDescription" />
      <MemberSignature Language="VB.NET" Value="ServiceFabricApplicationDescription" />
      <MemberSignature Language="F#" Value="ServiceFabricApplicationDescription = 1" Usage="System.Fabric.Description.ApplicationDefinitionKindFilter.ServiceFabricApplicationDescription" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8c629-106">定義されているアプリケーションに一致するフィルターを示します<see cref="T:System.Fabric.Description.ApplicationDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="8c629-106">Indicates a filter that matches applications defined by <see cref="T:System.Fabric.Description.ApplicationDescription" />.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>