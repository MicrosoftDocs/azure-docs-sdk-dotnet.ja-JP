<Type Name="ApplicationTypeDefinitionKindFilter" FullName="System.Fabric.Description.ApplicationTypeDefinitionKindFilter">
  <TypeSignature Language="C#" Value="public enum ApplicationTypeDefinitionKindFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ApplicationTypeDefinitionKindFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationTypeDefinitionKindFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum ApplicationTypeDefinitionKindFilter" />
  <TypeSignature Language="F#" Value="type ApplicationTypeDefinitionKindFilter = " />
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
      <para><span data-ttu-id="6fdfb-101">クエリによって返されるアプリケーションの種類の定義の種類の照合に使用されるフィルターを列挙します。</span><span class="sxs-lookup"><span data-stu-id="6fdfb-101">Enumerates the filters used for matching the definition kind of applications type that should be returned by query.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="6fdfb-102">この列挙体には、<see cref="T:System.FlagsAttribute" />そのメンバーのビットごとの組み合わせをできるようにします。</span><span class="sxs-lookup"><span data-stu-id="6fdfb-102">This enumeration has a <see cref="T:System.FlagsAttribute" /> that allows a bitwise combination of its members.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter All = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationTypeDefinitionKindFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 65535" Usage="System.Fabric.Description.ApplicationTypeDefinitionKindFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6fdfb-103">定義の種類のフィルターは追加されませんを示します。</span><span class="sxs-lookup"><span data-stu-id="6fdfb-103">Indicates no filter is added on definition kind.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Compose">
      <MemberSignature Language="C#" Value="Compose" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter Compose = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationTypeDefinitionKindFilter.Compose" />
      <MemberSignature Language="VB.NET" Value="Compose" />
      <MemberSignature Language="F#" Value="Compose = 2" Usage="System.Fabric.Description.ApplicationTypeDefinitionKindFilter.Compose" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6fdfb-104">定義されているし、作成する展開の一部として暗黙的に作成されたアプリケーションの種類に一致するフィルターを示します。</span><span class="sxs-lookup"><span data-stu-id="6fdfb-104">Indicates a filter that matches application types defined and created implicitly as part of a compose deployment.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationTypeDefinitionKindFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Description.ApplicationTypeDefinitionKindFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6fdfb-105">定義の種類のフィルターは追加されませんを示します。</span><span class="sxs-lookup"><span data-stu-id="6fdfb-105">Indicates no filter is added on definition kind.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ServiceFabricApplicationPackage">
      <MemberSignature Language="C#" Value="ServiceFabricApplicationPackage" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter ServiceFabricApplicationPackage = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationTypeDefinitionKindFilter.ServiceFabricApplicationPackage" />
      <MemberSignature Language="VB.NET" Value="ServiceFabricApplicationPackage" />
      <MemberSignature Language="F#" Value="ServiceFabricApplicationPackage = 1" Usage="System.Fabric.Description.ApplicationTypeDefinitionKindFilter.ServiceFabricApplicationPackage" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6fdfb-106">定義されているし、ユーザーが指定した Service Fabric アプリケーションのパッケージによって作成されたアプリケーションの種類に一致するフィルターを示します。</span><span class="sxs-lookup"><span data-stu-id="6fdfb-106">Indicates a filter that matches application types defined and created by a Service Fabric application package provided by the user.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>